[![arXiv](https://img.shields.io/badge/arXiv-2409.16099-B31B1B.svg)](https://arxiv.org/abs/2409.16099)
[![Poster](https://img.shields.io/badge/Poster-Download-blue)](https://your-link-to-poster.com)
![GitHub stars](https://img.shields.io/github/stars/MagriniGabriele/NeRDD?style=social)

# NeRDD
Repo for NeRDD dataset, comprising of more than 3.5 hours of spatio-temporally synced RGB-Event drone recordings.

To collect the data, a double-camera single-mount setup has been made, placing side-by-side an HD DVS camera and a standard RGB camera. 
In particular, the event-based camera is a Prophesee EVK4 HD, equipped with an 8mm optic and a Sony IMX636ES sensor. The RGB camera is a Svpro HD camera with varifocal lens and a resolution up to 1280x720 at 30fps.

The resulting dataset comprises 3.5 hours of multimodal recordings (a total of 7 hours of footage) at 30 FPS, divided into 115 different videos. Location and background activity significantly varies across videos. Both modalities have HD resolution ($1280 \times 720$).
A comparison of the NeRDD dataset with other event-based drone datasets is given in Tab. \ref{table:dataset_comparison}.

\begin{table}[t]
\begin{center}
\caption{Comparison of existing event-based drone datasets. Other datasets either have a low resolution, do not contain RGB versions of the samples, are not Drone-centric or are very small.}
\label{table:dataset_comparison}
\begin{tabular}{l|cccc}
%\hline
\textbf{Dataset}~ & ~\textbf{Resolution}~ & ~\textbf{RGB/Event}~ & ~\textbf{Hours}~ & ~\textbf{Drone-Centric}\\
\hline
\textbf{VisEvent\cite{wang2023visevent}} & 346 x 260 & \checkmark/\checkmark & <5 & $\times$\\
\hline
\textbf{EventVOT\cite{wang2024event}}~ &  ~1280 x 720 (HD) & $\times$/\checkmark & <5 & $\times$\\
\hline
\textbf{F-UAV-D\cite{mandula2024towards}} & ~1280 x 720 (HD)& \checkmark/\checkmark & 0.5 & \checkmark\\
\hline
\textbf{NeRDD}(Ours) & ~1280 x 720 (HD) & \checkmark/\checkmark & 3.5 & \checkmark \\
%\hline
\end{tabular}

\end{center}
\end{table}

LINK FOR THE DATASET COMING SOON.
