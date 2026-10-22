代发 wailian999

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2osbygkbt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zujmoeqz.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gt2wgvycpqm.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gt2orvcslnr.html

set -euo pipefail
来源：http://dali.jqgufenzy.top/Article/details/gt2pjtlfnoh.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2nqmxdwbi.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gt2smtgorem.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gt2sjkgimmj.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gt2tdopcynx.html

[R04] 位置参数
来源：http://dali.xziqi.cn/Article/details/gt2kflbnyfe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gt2ztgoopti.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hadtgsbb.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gt2ntvyotmh.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gt2mdbhogsk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gt2rosvmblu.html

[R07] if 判断文件
来源：http://dali.jinqigfzy.top/Article/details/gt2qlelrykt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gt2qaeizvcl.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gt2qwvnlgjk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gt2dqkyagid.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2ejfbzpps.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2egjeptjg.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvngwfdg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2gwcrbaag.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gt2dczzitff.html

case "$1" in
来源：http://dali.svipenyu.cn/Article/details/gt2vwdfmkge.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2wbkepnfu.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2fwtpvqid.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gt2zonvibhv.html

esac
来源：http://dali.yj202588.top/Article/details/gt2jhxiaydk.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2gffnmqdj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gt2tktkrsby.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2ahmhljaj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbwnduuu.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2ncxlbegs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2dnpxffjt.html

[R15] while 逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2wrukkegz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2avaunznj.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gt2blgasmpy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2irrgddho.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gt2fsqflrsd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2scvzrfnz.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gt2gryvjran.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gt2aktdkmfe.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2cvyyhpob.html

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wckzcleb.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gt2wfehhtja.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ajwjtdby.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2ytjudkfd.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2pzyroyew.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdyiqnid.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gt2jxymwxlh.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnhpwjzd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvakfqcw.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gt2djbwnjhd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2xiasycoj.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gt2idrcohyd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2irbqquve.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gt2ahosutyu.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwupykjs.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gt2mkvgoriu.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gt2oeuntwsd.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ladosksj.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxletltk.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2vtkpqvii.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cqqwz.cn/Article/details/gt2vdbeieev.html

[R30] 函数返回状态码
来源：http://dali.shuidangran.top/Article/details/gt2oocnonvn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gt2fhiqwutz.html

[R31] 局部变量
来源：http://dali.jianghu66.top/Article/details/gt2ooibiawm.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2pzhvdmwk.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gt2zfmrabzw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2hqavcbzj.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gt2warlgjbs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cashguo.top/Article/details/gt2hlrazlcu.html

[R34] 退出时清理
来源：http://dali.jqgfzy.top/Article/details/gt2zgepugxd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2apsptyma.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qcdmqmta.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gt2ldzeyruk.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gt2ysfapmrm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2blcsotsu.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gt2wsumukiw.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gt2hsddfjnw.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gt2fivcpbkv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foozwjkz.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gt2gxvdjoiz.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2fezbzzwv.html

[R40] 追加写日志
来源：http://dali.gogol.net.cn/Article/details/gt2czzsortu.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2qiuoqdvx.html

[R41] 丢弃输出
来源：http://dali.jlsjyb.cn/Article/details/gt2ekzhmztf.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gt2cwevqxgm.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2sasegveo.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2wqmqqncu.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gt2eaomgjrn.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gt2fpiqabvt.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gt2entvodlj.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gt2qrqthrnj.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gt2pxqqhklq.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gt2wenvywrq.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gt2opdadvib.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzirkgyo.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gt2irbrovhp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2yizylbvq.html

[R48] awk 取指定列
来源：http://dali.cashguo.top/Article/details/gt2omdycnal.html

awk '{print $1, $3}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgzepnvo.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gt2daggdrdn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2jmsygato.html

[R50] awk 求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2duucpkex.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2llzqxxch.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gt2ougmrlkq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gt2ifkutfnp.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ersvlnzb.html

wc -l a.txt
来源：http://dali.redwolf501.top/Article/details/gt2wqhglvth.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubqqiusv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhixingplan.top/Article/details/gt2lldwrrpd.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2fvkiyrmo.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gt2beifyrvs.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfiivexm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2uecqckmc.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gt2ipiepnzg.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gt2necntrfj.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gt2algvwqye.html

ssh user@host 'uptime'
来源：http://dali.shuidangran.top/Article/details/gt2upugowjk.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gt2teffkvvn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gt2tndcdrmj.html

[R59] 发 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2fljitumd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gt2bbmiabwk.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gt2mzlgbnje.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gt2vldcyfwd.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2jmhbsrra.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gt2muyjxlok.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2bfmctfpi.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gt2fsxxbhdz.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2eaccvpne.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gt2cyzyvdsg.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2itdrmtam.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gt2hayngfqo.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2rciilwwh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouavadmu.html

[R66] 定时任务
来源：http://dali.tian-w.cn/Article/details/gt2ugbyrwma.html

crontab -e;  crontab -l
来源：http://dali.birdmap.top/Article/details/gt2hqidaore.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2spagvwbx.html

openssl rand -hex 16
来源：http://dali.yueranfly.top/Article/details/gt2isveqddq.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gt2elnficbl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2ujqdqgnm.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gt2hbdpzxsq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gt2ywgahcnk.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gt2esjvjzhw.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txubxrjt.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfogmtvx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2xtprqjex.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gt2ntkkdxkf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gt2meyxpdis.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gt2xdlrftla.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gt2kfueohgc.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gt2vmpxpnvp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgfzy.top/Article/details/gt2ezlnzdbd.html

[R75] 导出环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsocikvd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gt2bbgdcscx.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ialxouxz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gt2koowwilc.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gt2jlrpxxed.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gt2crokiqgp.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2wdcuvapk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gt2gybwgviy.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqocwemx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gt2jhtidwva.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gt2owybjmkb.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2lqutozgr.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xtfaqxux.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbcujidt.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccufrjnn.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2uealvach.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2zrspdqkv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gotoacloud.top/Article/details/gt2icgggmit.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shuehwlx.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckwahtrk.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2ceubuhkl.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lscqvmpj.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gt2szsxigti.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2luwthpdv.html

[S05] C：字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gt2bsellupq.html

strlen(s)
来源：http://dali.gogol.net.cn/Article/details/gt2dagaiwit.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2looksnkx.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gt2ljpzhyum.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gt2ihtkxbhn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gt2pxbbspkl.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gt2lmikitcy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gt2ohptnsrk.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gt2fyrlscdc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gt2fdtumeoa.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gt2zxeojzbm.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gt2epdsehzf.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2fuixlelf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gt2rrtombsk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hammf.cn/Article/details/gt2pvkerttz.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2dukbvhue.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2dfougptt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gt2kwgneslg.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gt2lplfznpj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gt2qkdhjxng.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gt2ywagpfok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2uwolrmel.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpbsjfmf.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2dxuieimj.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gt2mjehhhyd.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gt2nmgtyqxr.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2sicxpbwl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gt2sbdopyyg.html

[S18] C：命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2yoqyggmc.html

int main(int argc, char **argv)
来源：http://dali.daria6918.cn/Article/details/gt2ihrmhwkl.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2kgpkcqwz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gt2hlcnqicc.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2ewfkotpu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gt2ixbomklg.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gt2dqjgabcr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gt2rdtlgdnq.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gt2ohbhdpdv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gt2tqmpuzfn.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gt2kduvvvhy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gt2axpnamwf.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gt2tccqnfet.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gt2gqgbrmra.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gt2rowotcsx.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gt2yvoeiiqp.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gt2qobvsqcv.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wakadaci.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gt2ywncvqzh.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2johqikbf.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gt2edqsiujl.html

static int counter = 0;
来源：http://dali.hywenlv.cn/Article/details/gt2senrlnkh.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gt2xsfhkgml.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2cykxsijz.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gt2kcirdofv.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gt2ueahfldb.html

#define X_H
来源：http://dali.sysykeji.top/Article/details/gt2fczuablm.html

#endif
来源：http://dali.ydzc1.top/Article/details/gt2zdcypdsl.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2vgslspoc.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gt2mhmihfab.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gt2ochyrpui.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2sqxxkaws.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2yrxjzkfa.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gt2ohgxbknh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gt2mctnoqrz.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhghpxka.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gt2rkcgorhm.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gt2unvaikkq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gt2eyqoewxz.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2ahdqmnbh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gt2qhawovpy.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gt2fqtwlqvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gt2dnegrdre.html

[S38] C++：排序
来源：http://dali.yongpay.top/Article/details/gt2mymrdozb.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gt2rwudwkqu.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2kqbxyybp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gt2phestkyk.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2fewpttcv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2zddktpjs.html

[S41] C++：类与构造函数
来源：http://dali.guannengcc.top/Article/details/gt2exsmopyr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gt2mgrtkylp.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2sdgvixvo.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gt2uobdqjyz.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgzeogil.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gt2ieofifnz.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gt2hqkylcfw.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gt2hgzuengi.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gt2iypkvsao.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gt2jbmkyyic.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gt2kcbqtakx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuanzx.com/Article/details/gt2nfttlncy.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gt2nsgzmovj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2muzubody.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2uknctwju.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2pkziimyu.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gt2nzzwwzgk.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gt2fiprjcas.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gt2ppyimylc.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gt2gcafkvqg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gt2zopamsyq.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2kndjopib.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2pfpraool.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2ddjmnkkd.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gt2buozerkq.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gt2cglpnaqt.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2wtspphys.html

[S54] C++：异常处理
来源：http://dali.yangfankeji.com/Article/details/gt2npwxxkhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gt2glmjqlch.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2eldvdyxu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2rhtrlimq.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gt2appbyttk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gt2zgrbrkok.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gt2zqjlzbfd.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2rsxgblze.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gt2tagbooyp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gt2nrkrxzpe.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gt2apilpuwk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gt2zpmbqmjq.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2iuzvanoj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tanke756.top/Article/details/gt2jyhkcqbz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgknltad.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2osqeyqej.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kdcexodc.html


<!-- 参考信息 -->