# open-CV
openCV

01、openCV安装
>>>
一. 安装OpenCV库：
打开终端，输入以下命令安装OpenCV：
sudo apt-get update
sudo apt-get install libopencv-dev
库默认安装在了这个目录
usr/lib/x86_64-linux-gnu/libopencv_videostab.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_stereo.a
/usr/lib/x86_64-linux-gnu/libopencv_stitching.a
/usr/lib/x86_64-linux-gnu/libopencv_imgcodecs.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_videostab.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_calib3d.so
/usr/lib/x86_64-linux-gnu/libopencv_surface_matching.a
/usr/lib/x86_64-linux-gnu/libopencv_video.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_video.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_core.a
/usr/lib/x86_64-linux-gnu/libopencv_dnn_superres.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_text.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_imgcodecs.so
/usr/lib/x86_64-linux-gnu/libopencv_hfs.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_phase_unwrapping.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_ximgproc.so
/usr/lib/x86_64-linux-gnu/libopencv_tracking.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_imgproc.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_line_descriptor.a
/usr/lib/x86_64-linux-gnu/libopencv_rgbd.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_calib3d.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_dpm.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_structured_light.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_face.a
/usr/lib/x86_64-linux-gnu/libopencv_reg.so
/usr/lib/x86_64-linux-gnu/libopencv_ximgproc.a
/usr/lib/x86_64-linux-gnu/libopencv_fuzzy.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_xphoto.a
/usr/lib/x86_64-linux-gnu/libopencv_quality.a
/usr/lib/x86_64-linux-gnu/libopencv_dpm.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_datasets.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_bioinspired.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_structured_light.so
/usr/lib/x86_64-linux-gnu/libopencv_ccalib.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_highgui.a
/usr/lib/x86_64-linux-gnu/libopencv_tracking.a
/usr/lib/x86_64-linux-gnu/libopencv_imgcodecs.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_ccalib.a
/usr/lib/x86_64-linux-gnu/libopencv_hdf.so
/usr/lib/x86_64-linux-gnu/libopencv_stereo.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_ccalib.so
/usr/lib/x86_64-linux-gnu/libopencv_videoio.so.4.2
/usr/lib/x86_64-linux-gnu/cmake/opencv4
/usr/lib/x86_64-linux-gnu/libopencv_bioinspired.so
/usr/lib/x86_64-linux-gnu/libopencv_quality.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_hfs.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_datasets.a
/usr/lib/x86_64-linux-gnu/libopencv_structured_light.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_xobjdetect.a
/usr/lib/x86_64-linux-gnu/libopencv_imgproc.a
/usr/lib/x86_64-linux-gnu/libopencv_superres.a
/usr/lib/x86_64-linux-gnu/libopencv_features2d.a
/usr/lib/x86_64-linux-gnu/libopencv_saliency.a
/usr/lib/x86_64-linux-gnu/libopencv_calib3d.a
/usr/lib/x86_64-linux-gnu/libopencv_dnn_superres.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_plot.so
/usr/lib/x86_64-linux-gnu/libopencv_viz.a
/usr/lib/x86_64-linux-gnu/libopencv_flann.a
/usr/lib/x86_64-linux-gnu/libopencv_hdf.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_text.a
/usr/lib/x86_64-linux-gnu/libopencv_optflow.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_aruco.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_photo.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_datasets.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_plot.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_phase_unwrapping.so
/usr/lib/x86_64-linux-gnu/libopencv_bgsegm.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_tracking.so
/usr/lib/x86_64-linux-gnu/libopencv_phase_unwrapping.a
/usr/lib/x86_64-linux-gnu/libopencv_ximgproc.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_text.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_text.so
/usr/lib/x86_64-linux-gnu/libopencv_superres.so
/usr/lib/x86_64-linux-gnu/libopencv_ts.a
/usr/lib/x86_64-linux-gnu/libopencv_plot.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_stitching.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_ccalib.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_features2d.so
/usr/lib/x86_64-linux-gnu/libopencv_fuzzy.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_imgproc.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_core.so
/usr/lib/x86_64-linux-gnu/libopencv_dnn.a
/usr/lib/x86_64-linux-gnu/libopencv_plot.a
/usr/lib/x86_64-linux-gnu/libopencv_highgui.so
/usr/lib/x86_64-linux-gnu/libopencv_flann.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_img_hash.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_img_hash.a
/usr/lib/x86_64-linux-gnu/libopencv_imgproc.so
/usr/lib/x86_64-linux-gnu/libopencv_surface_matching.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_features2d.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_bgsegm.a
/usr/lib/x86_64-linux-gnu/libopencv_img_hash.so
/usr/lib/x86_64-linux-gnu/libopencv_videoio.a
/usr/lib/x86_64-linux-gnu/libopencv_dnn_objdetect.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_dnn.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_stitching.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_img_hash.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_xobjdetect.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_xobjdetect.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_line_descriptor.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_objdetect.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_objdetect.so
/usr/lib/x86_64-linux-gnu/libopencv_shape.a
/usr/lib/x86_64-linux-gnu/libopencv_features2d.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_fuzzy.so
/usr/lib/x86_64-linux-gnu/libopencv_freetype.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_highgui.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_freetype.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_phase_unwrapping.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_hdf.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_rgbd.so
/usr/lib/x86_64-linux-gnu/libopencv_fuzzy.a
/usr/lib/x86_64-linux-gnu/libopencv_core.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_line_descriptor.so
/usr/lib/x86_64-linux-gnu/libopencv_viz.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_hdf.a
/usr/lib/x86_64-linux-gnu/libopencv_aruco.a
/usr/lib/x86_64-linux-gnu/libopencv_shape.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_flann.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_reg.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_hfs.so
/usr/lib/x86_64-linux-gnu/libopencv_rgbd.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_objdetect.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_face.so
/usr/lib/x86_64-linux-gnu/libopencv_freetype.so
/usr/lib/x86_64-linux-gnu/libopencv_ml.so
/usr/lib/x86_64-linux-gnu/libopencv_stitching.so
/usr/lib/x86_64-linux-gnu/libopencv_core.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_dpm.a
/usr/lib/x86_64-linux-gnu/libopencv_dnn_objdetect.so
/usr/lib/x86_64-linux-gnu/libopencv_video.so
/usr/lib/x86_64-linux-gnu/libopencv_ml.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_stereo.so
/usr/lib/x86_64-linux-gnu/libopencv_viz.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_video.a
/usr/lib/x86_64-linux-gnu/libopencv_freetype.a
/usr/lib/x86_64-linux-gnu/libopencv_highgui.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_ml.a
/usr/lib/x86_64-linux-gnu/libopencv_stereo.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_dnn_objdetect.a
/usr/lib/x86_64-linux-gnu/libopencv_superres.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_flann.so
/usr/lib/x86_64-linux-gnu/libopencv_dnn.so
/usr/lib/x86_64-linux-gnu/libopencv_hfs.a
/usr/lib/x86_64-linux-gnu/libopencv_saliency.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_dpm.so
/usr/lib/x86_64-linux-gnu/libopencv_optflow.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_saliency.so
/usr/lib/x86_64-linux-gnu/libopencv_bgsegm.so
/usr/lib/x86_64-linux-gnu/libopencv_superres.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_quality.so
/usr/lib/x86_64-linux-gnu/libopencv_ml.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_reg.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_aruco.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_dnn_superres.a
/usr/lib/x86_64-linux-gnu/libopencv_xphoto.so
/usr/lib/x86_64-linux-gnu/libopencv_viz.so
/usr/lib/x86_64-linux-gnu/libopencv_videostab.a
/usr/lib/x86_64-linux-gnu/libopencv_structured_light.a
/usr/lib/x86_64-linux-gnu/libopencv_reg.a
/usr/lib/x86_64-linux-gnu/libopencv_imgcodecs.a
/usr/lib/x86_64-linux-gnu/libopencv_shape.so
/usr/lib/x86_64-linux-gnu/libopencv_dnn_superres.so
/usr/lib/x86_64-linux-gnu/pkgconfig/opencv4.pc
/usr/lib/x86_64-linux-gnu/libopencv_bioinspired.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_ximgproc.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_rgbd.a
/usr/lib/x86_64-linux-gnu/libopencv_surface_matching.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_surface_matching.so
/usr/lib/x86_64-linux-gnu/libopencv_calib3d.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_photo.a
/usr/lib/x86_64-linux-gnu/libopencv_saliency.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_optflow.a
/usr/lib/x86_64-linux-gnu/libopencv_videoio.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_dnn_objdetect.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_face.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_xobjdetect.so
/usr/lib/x86_64-linux-gnu/libopencv_photo.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_dnn.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_aruco.so
/usr/lib/x86_64-linux-gnu/libopencv_xphoto.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_photo.so
/usr/lib/x86_64-linux-gnu/libopencv_bgsegm.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_line_descriptor.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_shape.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_bioinspired.a
/usr/lib/x86_64-linux-gnu/libopencv_tracking.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_objdetect.a
/usr/lib/x86_64-linux-gnu/libopencv_face.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_xphoto.so.4.2
/usr/lib/x86_64-linux-gnu/libopencv_videoio.so
/usr/lib/x86_64-linux-gnu/libopencv_datasets.so
/usr/lib/x86_64-linux-gnu/libopencv_quality.so.4.2.0
/usr/lib/x86_64-linux-gnu/libopencv_videostab.so
/usr/lib/x86_64-linux-gnu/libopencv_optflow.so
/usr/lib/jni/libopencv_java420.so
头文件安装在了这个目录
/usr/include/opencv4
/usr/include/opencv4/opencv2
/usr/include/opencv4/opencv2/opencv_modules.hpp
/usr/include/opencv4/opencv2/opencv.hpp
/usr/include/boost/compute/interop/opencv.hpp
/usr/include/boost/compute/interop/opencv
02、Qt 配置openCV
>>>
在Qt Creator中打开项目，然后编辑.pro文件，添加以下内容：




QT       += core gui
​
greaterThan(QT_MAJOR_VERSION, 4): QT += widgets
​
CONFIG += c++17
​
# You can make your code fail to compile if it uses deprecated APIs.
# In order to do so, uncomment the following line.
#DEFINES += QT_DISABLE_DEPRECATED_BEFORE=0x060000    # disables all the APIs deprecated before Qt 6.0.0
​
SOURCES += \
    main.cpp \
    mainwindow.cpp
​
HEADERS += \
    mainwindow.h
​
FORMS += \
    mainwindow.ui
​
# Default rules for deployment.
qnx: target.path = /tmp/$${TARGET}/bin
else: unix:!android: target.path = /opt/$${TARGET}/bin
!isEmpty(target.path): INSTALLS += target
​
​
# openCV
INCLUDEPATH += /usr/include/opencv4
LIBS += -L/usr/lib/x86_64-linux-gnu/ -lopencv_core -lopencv_imgproc -lopencv_highgui -lopencv_imgcodecs
​
RESOURCES += \
    images.qrc
​
03、Qt openCV 测试
>>>
图像变灰 演示



04、mainwindow.h
#ifndef MAINWINDOW_H
#define MAINWINDOW_H
​
#include <QMainWindow>
​
QT_BEGIN_NAMESPACE
namespace Ui {
class MainWindow;
}
QT_END_NAMESPACE
​
class MainWindow : public QMainWindow
{
    Q_OBJECT
​
public:
    MainWindow(QWidget *parent = nullptr);
    ~MainWindow();
​
private slots:
    void on_pushButton_clicked();
​
private:
    Ui::MainWindow *ui;
};
#endif // MAINWINDOW_H
​
05、mainwindow.cpp
#include "mainwindow.h"
#include "ui_mainwindow.h"
​
#include <opencv2/opencv.hpp>
#include <QImage>
#include <QPixmap>
​
MainWindow::MainWindow(QWidget *parent)
    : QMainWindow(parent)
    , ui(new Ui::MainWindow)
{
    ui->setupUi(this);
    // 实现图片按标签大小适应而不失真。
    QPixmap pixmap1("/home/whois/Qt_openCV_TEST/images/girl.png");
    ui->label_2->setPixmap(pixmap1.scaled(ui->label_2->size(), Qt::KeepAspectRatio, Qt::SmoothTransformation));
​
    // 实现图片按标签大小适应而不失真。
    QPixmap pixmap2("/home/whois/Qt_openCV_TEST/images/girl.png");
    ui->label_3->setPixmap(pixmap2.scaled(ui->label_3->size(), Qt::KeepAspectRatio, Qt::SmoothTransformation));
}
​
MainWindow::~MainWindow()
{
    delete ui;
}
​
// opencv
void MainWindow::on_pushButton_clicked()
{
    // 读取原始图像
    cv::Mat img = cv::imread("/home/whois/Qt_openCV_TEST/images/girl.png");
    if (img.empty()) {
        qDebug() << "Image not found!";
        return;
    }
​
    // 将图像转换为灰度图
    cv::Mat grayImg;
    cv::cvtColor(img, grayImg, cv::COLOR_BGR2GRAY);
​
    // 将灰度图像转换为QImage
    QImage qImg((const unsigned char*)(grayImg.data), grayImg.cols, grayImg.rows, grayImg.step, QImage::Format_Grayscale8);
​
    // 显示灰度图像到标签上
    ui->label_3->setPixmap(QPixmap::fromImage(qImg.scaled(ui->label_3->size(), Qt::KeepAspectRatio, Qt::SmoothTransformation)));
}
06、mainwindow.ui


07、main.cpp
#include "mainwindow.h"
​
#include <QApplication>
​
int main(int argc, char *argv[])
{
    QApplication a(argc, argv);
    MainWindow w;
    w.show();
    return a.exec();
}
​
08、图片素材
>>>




09、openCV 解读
>>>
OpenCV（Open Source Computer Vision Library）是一个开源的计算机视觉库，广泛应用于多个领域。以下是一些主要的应用场景：

图像处理：

图像的平滑、锐化、边缘检测等基本操作。

色彩空间转换（例如RGB到灰度、HSV等）。

人脸识别：

实时人脸检测和识别，用于安防监控、用户身份验证等领域。

物体检测和跟踪：

在视频监控、自动驾驶等场景中，识别和跟踪特定物体，如车辆、行人等。

图像拼接：

将多张图片组合成全景图像，常用于摄影和游戏等领域。

OCR（光学字符识别）：

从图片中提取文本信息，应用于文档数字化和自动化数据录入。

机器学习和深度学习：

利用OpenCV与TensorFlow、PyTorch等深度学习框架结合，实现更复杂的视觉任务。

增强现实：

在实时视频中叠加虚拟对象，用于游戏、教育和培训等场景。

工业自动化：

机器视觉在生产线上的应用，例如缺陷检测和质量控制。

医学影像处理：

处理和分析医学图像，如CT、MRI图像，用于疾病诊断。

这些应用展示了OpenCV在各个行业的广泛适用性，通过其强大的图像处理和分析能力，推动了智能化的发展。
