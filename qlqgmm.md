代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2njjrjtaa.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gt2equqvyto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gt2zndabrmx.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2cmapdlvt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2ncicsgso.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2oookgjhm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gt2ynjtaliv.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2fdiojikz.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gt2vvtyuddr.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2tsyrvwgj.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2dltnozhc.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2oezejaky.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2rasqrtfm.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gt2akjnbsey.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gt2jvtlqwfg.html

[R13] for 计数循环
来源：http://dali.yuxming.cn/Article/details/gt2qnfffveq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2ixkwpzuh.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gt2ebtdgjki.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2kzgsrebj.html

[R15] while 逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfrnxaqw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gt2eexjyrdz.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2nqcyydkl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gt2vbcncmkc.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkmiulng.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gt2tnnzmscx.html

[R18] 遍历数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2gpudiwyz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gt2jxxkehbs.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2ejmpoygh.html

echo "${#arr[@]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmwlgnmc.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2ifjaqdnt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2jqmiroiw.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2owirfuky.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gt2sohccxfz.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2xtfqwndt.html

echo "${s:0:5}"
来源：http://dali.ydzc1.top/Article/details/gt2thysyphm.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2sdrrciak.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2pirhsrug.html

[R24] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gt2cuzzmtal.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gt2jttfrfxj.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gt2ykyyihig.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2ygtyarxq.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gt2zxfncfla.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gt2cjoneewh.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gt2rqmuroej.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrkwfzkd.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gt2utbpmnov.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gt2lydpiaee.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2usiuwqqg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2usftsfbq.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2ogxclxdc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gt2reshfdqf.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gt2kuyehpdb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gt2ndsmevxj.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gt2ahmtcemq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fozixjrt.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gt2cduboryf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhongyouzk.top/Article/details/gt2qafhxtfw.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gt2qohohsdt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gt2ireubzeg.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftvyziqy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gt2sendzdwh.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2bgxladte.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gt2nyydbztk.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gt2zkjoqcnc.html

files=$(ls -1)
来源：http://dali.c1oappe.top/Article/details/gt2gktqigym.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gt2nghjgaxb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2pwncoehu.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2ehkmhexi.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gt2wzqfvksg.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sglkkmgs.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gt2urjrwnev.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2udawuqwf.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2iwxwxfzd.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aipqpvyk.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gt2zqfvmhep.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gt2jsfupkgz.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2soigpnkz.html

[R44] 按修改时间查找
来源：http://dali.kuanghao11.cn/Article/details/gt2ahuvqtns.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gt2rplffrfv.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gt2chvffdwu.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2viqehwyj.html

[R46] 递归替换文件内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2viqilfpt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2arvizodn.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gt2uiarowne.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2rrpwprhr.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gt2qfyfnkeo.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2rompjhbi.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fytshqaq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gt2qnenxkgd.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gt2beuxpfpm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2wurvgvjb.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2toddbhty.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2gwvzxgvq.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gt2fiwvtfoj.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gt2natfuxcg.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gt2jhcbfpve.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gt2qbqobtzs.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gt2fxvusdwm.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gt2rzyhckim.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2ofzxeurk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gt2mkntsaag.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gt2mxsvfmch.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2ggbyorit.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyhfnnnt.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gt2fzmyeasv.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2igpvzbsb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ppjwa.cn/Article/details/gt2gcecwkmo.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2slyjdnky.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gt2cywgpzio.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwgiqilc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2iobmgjqi.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkytqrfy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zilgkypc.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gt2vsnbkwbp.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2nqxepdww.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gt2gqlhdodz.html

free -h;  ps aux | grep nginx
来源：http://dali.xylfe.cn/Article/details/gt2qggstmnh.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozrgtpce.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mdocuvod.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2wuuzjgdk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gt2ifenctrx.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gt2dwpkmukw.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gt2seskowna.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqyzuvaj.html

openssl rand -hex 16
来源：http://dali.vqdsnc.cn/Article/details/gt2gmwborst.html

[R68] 计算文件校验值
来源：http://dali.guannengcc.top/Article/details/gt2malmawyy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2rwvaliue.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gt2csevdxrw.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2ragkrrxx.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gt2ksiwrcbf.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2auwnwihu.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2xpivcnjv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2qpbldiem.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvdcnrpe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2nljybsrz.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gt2iigqnuqq.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gt2docueyqx.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gt2gtinrhbj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2flfhhoqb.html

[R75] 导出环境变量
来源：http://dali.xuanzx.com/Article/details/gt2rntvhfjf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2ywxrmvme.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtzlksoz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2sfovlzvp.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gt2xcxteans.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gt2sltmxxla.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gt2utykjpcd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gt2odgfwyxr.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gt2oiegdvcz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2pizauhlt.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2fhykysuw.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gt2ckfvfepx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lqlbkvqi.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gt2aftxvpnq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qxdgiwto.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2ievjwwbv.html

#include <stdio.h>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzjcdwzg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gt2xbzbyeab.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2hvmqfusc.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gt2razlmnka.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doqhujjw.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gt2dzprbpmr.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2gogzgvjn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2ihbpoyei.html

[S05] C：字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2lixwmdtz.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gt2moxyvknx.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2zldiyboe.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gt2xttllusd.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gt2typonabh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2flkirupn.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gt2rftnonfn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gt2sjaofjez.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2ojgcllmb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gt2tcubotda.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtzlygow.html

int *p = &a;  *p = 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2xejgvopm.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gt2tvkryosz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gt2pbuvuoay.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gt2xmjkykky.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2wwpixspc.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2zywztewa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htevsyea.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gt2gmcmsldr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gt2txcttzrp.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2jmrajpag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjxvsrml.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gt2oujkmycb.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gt2olvswxiq.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gt2sgfwehsn.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gt2aipwjwbm.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2xudtummv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gt2qxoalmbx.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2vlogjgte.html

int main(int argc, char **argv)
来源：http://dali.jlsjyb.cn/Article/details/gt2lljjeqfo.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gt2ylegwmbr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gt2favlgqbz.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gt2rsjlqpoo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2zomptdgw.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anbbeojd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gt2djymcekd.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gt2nmhplkhh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2txfezjst.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gt2mgddrgix.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toqqrjhx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2crzyuzvn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2bftgwwdx.html

[S25] C：内存拷贝
来源：http://dali.ppjwa.cn/Article/details/gt2egigwvye.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2lcqtuzra.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2arsevfkw.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2svlkfocv.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2uiyedxgf.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2mnrhamgf.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gt2nspclplr.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2ysgshxmf.html

[S29] C：变参函数
来源：http://dali.gzhubu.top/Article/details/gt2vncvbkze.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gt2zarqjezf.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cefsvibl.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gt2yiywxsoz.html

#define X_H
来源：http://dali.gzhubu.top/Article/details/gt2ogkdbttj.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gt2rvfknuax.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2psetjplg.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gt2vwfvhoex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wpkdaulm.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gt2xixqgpoa.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gt2clfpotak.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2tibyxwvx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gt2ibpvyvgm.html

[S34] C++：遍历 vector
来源：http://dali.ydzc1.top/Article/details/gt2eccgdlyi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thsbazcg.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndntgcls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2jocmzexh.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqhqfmuj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2bwkmmilv.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2popnywds.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqosvpmj.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cqepnwky.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2efeovzqu.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gt2pjcxhtrr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppkndvqf.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2oualvolh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2valezlst.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2drexnubv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gt2lwcdbwgk.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gt2pklznbrk.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzvaaqto.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gt2jgpchseh.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gt2octxmepb.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gt2pdtujhev.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gt2ldnyiwys.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gt2jbvumoke.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2enwvlzor.html

[S46] C++：函数模板
来源：http://dali.yj202588.top/Article/details/gt2ijygbnlq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gt2exygzljp.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2qvqxpyvv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gt2yoqmoqty.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gt2hmttfcka.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gt2hsrlcmfw.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gt2eajqsrwg.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gt2lzaecxlg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gaohongyu789.top/Article/details/gt2fcmmeoaw.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gt2uvuahtkg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fywizowy.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gt2bktvxews.html

static_cast<double>(a) / b
来源：http://dali.redwolf501.top/Article/details/gt2evmosyxv.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2inhulplh.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gt2rjpieoyc.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gt2iijtpoco.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2xnnxrtky.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gt2whqztihb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gt2ygjsvvfh.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gt2zdosvftp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gt2ocsreihl.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gt2hcuxelys.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wzxehtib.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxksrrse.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gt2chmyrgcj.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2cdntdhnk.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gt2qojtttns.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gt2uwgojxqy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gt2nadeontd.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gt2ntmsvhct.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2bahngtuz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2chkfpncx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gt2tlryapim.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2dhfhupet.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2lcjfeihq.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nmoamxmy.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2qcsacalz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gt2nwzbhhul.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gt2noxppjvv.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wcvtkeea.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2ozzmhefh.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gt2xsbtjzdo.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2zghxendh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gt2vrfddlxc.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gt2wytpqcrt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxubxfza.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2cihgflky.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gt2fcgijmju.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gt2olystowb.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mquygkhx.html


<!-- 参考信息 -->