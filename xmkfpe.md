代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gt2lkdyjdfx.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gt2zjykdmql.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.9152youxi.cn/Article/details/gt2xgxpykqc.html

[R09] 字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2jtrusxkb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2kgousrag.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hadosrbo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gt2lgviftgf.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gt2eogasmcb.html

case "$1" in
来源：http://dali.yonumen.top/Article/details/gt2duzlxiou.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gt2wibhfefa.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gt2fixazpys.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gt2lcbkbfyf.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwolhzvq.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gt2vphuxmvp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2cozslqyl.html

[R13] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gt2wgzdrwla.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2nhnfkhio.html

[R14] C 风格 for
来源：http://dali.gaohongyu789.top/Article/details/gt2iagctrtp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2chtdvcdj.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2tonxeztf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gt2qmhdksia.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gt2qnsibphx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2djfgydim.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2dtdjapwo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2ooimdtnp.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gt2dtbocnyx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2pvqzopqy.html

[R19] 数组长度
来源：http://dali.yongpay.top/Article/details/gt2vxiqcxll.html

echo "${#arr[@]}"
来源：http://dali.xylfe.cn/Article/details/gt2enxjjppz.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gt2lnfexrwu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2ebiznrmh.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gt2bikgkqrg.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gt2xnczgnbs.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzovfyas.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2dyytnfmn.html

[R23] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gt2fmerqpik.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gt2qdyevavc.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gt2oysaqzly.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2pihdqlhx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gt2kpjqbryd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gt2vxhyvwvw.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyvofaxk.html

now=$(date +%F); echo "$now"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgnpkiic.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gt2lsifbzxp.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxowkvvv.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gt2vknnmade.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gt2oanunggw.html

[R29] 定义函数
来源：http://dali.yuxming.cn/Article/details/gt2kslktekr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gt2tjwtaqer.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2cgtsnogw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjzirtha.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gt2paqcktbn.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2angywmip.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gt2twoyupbn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gt2fiwbswjc.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gt2vhcqhftz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frjqdybc.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gt2kkoqdjzd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gt2kjjvptmo.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2ujaweupa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gt2uaktfcui.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gt2juqdicdt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sufxvd.cn/Article/details/gt2ygnrotbt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyelqpeh.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gt2eypznukz.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gt2ibmylhpl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gt2yecxjmae.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gt2wwkycxzz.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gt2cqiqrzxf.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gt2bzykukts.html

echo "log" >> out.log
来源：http://dali.vqdsnc.cn/Article/details/gt2hjjgufqg.html

[R41] 丢弃输出
来源：http://dali.xylfe.cn/Article/details/gt2rqqyocvl.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2vxefokiy.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2pczleqxv.html

wc -l < a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2izhtwuie.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gt2fozilyeu.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gt2apzvzauf.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gt2htwwmoxl.html

find . -mtime -7 -type f
来源：http://dali.daxiang520.top/Article/details/gt2jokpxldc.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gt2mylepepy.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gt2npmjgbss.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gt2bdgorkxl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.haohaochexian.top/Article/details/gt2qrhbohdj.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gt2nxnjtpcm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2axxirxfo.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gt2qhzstczu.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbptzyko.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2kwjzndue.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gt2jngkulss.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gt2nngmdtrj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbgqurfu.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gt2vedmxjqj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gt2aasseacr.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gt2cwgxsghr.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2zzjnzudm.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gt2dfrauogj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2vsyzsxtl.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2pjhazjcd.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gt2aqkxhskf.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2nyzjfbrk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2seajurku.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dghwksgs.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2ozptuhbg.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2rbgtuniu.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2zqdfetji.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gt2alxvrtbc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2doqnshvx.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2qfthurfm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ehwqpu.com/Article/details/gt2yowzuqel.html

[R60] 只看 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gt2cxeppyzg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gt2xypcgvdl.html

[R61] 磁盘占用
来源：http://dali.chenlongwang.top/Article/details/gt2bgklhrvt.html

df -h;  du -sh *
来源：http://dali.havefunace.top/Article/details/gt2sidhratb.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gt2tkuillxm.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gt2sokqzcbn.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gt2qeuefwuv.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gt2nslwuiyg.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gt2wzruilqv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gt2rcuvvpll.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gt2ojljeaqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2huotyuda.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mppjfuan.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxqnodfd.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gt2aupqpvcq.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gt2ocslgezx.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2unrdkfmd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gt2axurzmdc.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gt2ugvkkikb.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlzlfgjn.html

[R70] 时间戳与互转
来源：http://dali.vqdsnc.cn/Article/details/gt2zoqpxydx.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gt2pswmswze.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2cycolteo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2pgnehuft.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gt2ggqzprsx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gt2vgxppsaf.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gt2jgmgptmk.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gt2grkaebex.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2vxipwpkl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcgwkkq.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2bhbyhgbb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gt2dzdzlspx.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gt2fualmuyf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2gjdtrfmw.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gt2utlyvfht.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gt2lcypgvtt.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2kmwhfrvm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gt2ndmdkurx.html

[R79] 解析命令行选项
来源：http://dali.xuanzx.com/Article/details/gt2yyckpxca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gt2cugdewty.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gt2ticlryds.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2cjnadkxd.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2wqfibdxd.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2yqdepbxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2roedsnux.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2nczexxly.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gt2uedgvtil.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gt2urfnuwaw.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqcifkma.html

int a = 10; printf("%d\n", a);
来源：http://dali.gogol.net.cn/Article/details/gt2lzcsncax.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmrzibuk.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2hladokhz.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gt2dotxwbdr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2zuxrtnsu.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2lnnhmdmh.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gt2llwkglpz.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2toiyhkmu.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2oghvtuxw.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gt2xqkaqtfu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2uzwvkmse.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gt2jstheksp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfgxozqw.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gt2flymepra.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gt2mtcgtbrv.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gt2ccagddli.html

int *p = &a;  *p = 5;
来源：http://dali.yonumen.top/Article/details/gt2eskhpghm.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gt2tnsdcfjh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gt2jrimmgnb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuanzhike.top/Article/details/gt2nlqrseci.html

fclose(f);
来源：http://dali.c1oappe.top/Article/details/gt2xjdjcwnr.html

[S12] C：写文件
来源：http://dali.jlsjyb.cn/Article/details/gt2nwwlodmr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gt2hicaonpk.html

[S13] C：宏定义
来源：http://dali.guowangkeji.top/Article/details/gt2mznmxjtk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gt2hkisbtue.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2yxpnxsas.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gt2eljqvoad.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gt2vnzstjnx.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gt2qujhrico.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fhvfjnhd.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gt2jeueplat.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2dlfakbdn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258.top/Article/details/gt2kisbtubl.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwabvtga.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2yiiyllwk.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gt2joagseth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gt2pdanuolt.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srftmffz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2jrloqypb.html

[S21] C：字符类别判断
来源：http://dali.cucudq.cn/Article/details/gt2hddsekrf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gt2sxtylblb.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gt2enueelxl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.guannengcc.top/Article/details/gt2turkuhrm.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gt2bnihmajl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gt2ioaegdto.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttowrufw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2sybpzmrc.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gt2oysqmwzc.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gt2wumzbhkm.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2nxbaepfk.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gt2tptfhsxu.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gt2wxekkxpy.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2xfmaafdb.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gt2qbllsusb.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gt2xzwwoxbq.html

[S29] C：变参函数
来源：http://dali.shuidangran.top/Article/details/gt2lkzkjepu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gt2szcinwxn.html

[S30] C：头文件保护
来源：http://dali.gzhubu.top/Article/details/gt2xqhkeyhv.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gt2dovxgxwy.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2tbizghnh.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gt2thglbpre.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2gtyceydy.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gt2wipkbmog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gt2gqdddyou.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2ajglbbhr.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gt2pgfeajqp.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gt2rllhdfwl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2osihuxck.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gt2nuyntwdj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gt2zauysyww.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2deynuafc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2puehgors.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gt2vrwekhte.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2hfwxkkcm.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gt2lfbsejef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2lcfsgkow.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gt2tpzacdns.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2pqirnbko.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdgrcxne.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gt2vgjsxyvp.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbggfjik.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gt2givsrted.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2uqjqtqsp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2uxrxgpad.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2pbwygxjs.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rionpmxe.html

[S43] C++：智能指针
来源：http://dali.yueranfly.top/Article/details/gt2znzujmkr.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gt2hsiqjnle.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gt2uwrnlxhq.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gt2uibuogvh.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gt2hsftgljt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gt2cigclnkh.html

[S46] C++：函数模板
来源：http://dali.aizwys.cn/Article/details/gt2wufxghwa.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gt2wkyfodto.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2mutybpjd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2fzcpkhsl.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2xphspjqh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gt2hxypcdwf.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2erivehqw.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gt2eryychmt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2psoloica.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gt2lsilygmd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ipvyexyi.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzcibjmq.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gt2ezozrjad.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gt2tdvxijkp.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fffwuogg.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gt2jcbkuqee.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gt2pkvoulss.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2ooyqycvi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2drcodknp.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onxalkff.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2ymoxahrw.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gt2klxgatjn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gt2svccrioy.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gt2tusrvjbv.html

constexpr int N = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kbpitgry.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gt2znnnpkho.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gt2jiltwwrf.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gt2xqaceevg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ppjwa.cn/Article/details/gt2zczhorje.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gt2qdukpuhd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2geawjjbc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qyzajgci.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gt2qwycawod.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dtvcolws.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258.top/Article/details/gt2zepbdtkm.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2jvciuffq.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2eohbrxzl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gt2wsqjyofe.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gt2rsbnrtjb.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2egwrxuml.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfcmoamt.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2wlgwbbrd.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxlpuqfq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258.top/Article/details/gt2svqvtdgc.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gt2sehvevvb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2dhnugifp.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2ccbhfkom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gt2iziubkcx.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2qbadchcl.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gt2ksamhljr.html


<!-- 参考信息 -->