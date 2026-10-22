代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ukcsxquj.html

[R14] C 风格 for
来源：http://dali.dianchejie.cn/Article/details/gt2gwmebjgs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2ggnitusp.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzcibsly.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gt2ozbegihc.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpsgimaz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkgsxxst.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gt2jrcoqwgt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2kqtzcyka.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gt2qwzoudow.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gt2avghfbvb.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2cwelvocg.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gt2xcrsgado.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gt2bbjnqsmv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gt2gsqaffml.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyhhzrdo.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2odolslgm.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2qnmuuclt.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2ivmviagm.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2qeobwkka.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gt2gbvcdmyn.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gt2pcoplyqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2eaqtpgrs.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2hoggtnjz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtxbgsl.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gt2qggbrvof.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2schggrji.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2njjfiify.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gt2nmkrsjho.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gt2drbttuxm.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gt2fgdxmacy.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gt2nmfksrnv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2zoweokjv.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gt2mpilaxye.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvtbkgzi.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gt2ysjjysbl.html

f() { local x=1; echo "$x"; }
来源：http://dali.xinyue.icu/Article/details/gt2qqtamgss.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gt2joykcssb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2aquyjzwi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwgjpgds.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gt2pbgaokvf.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gt2wwrlblyh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2jashfiws.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gt2tgrlyjnx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2yjhstrbb.html

[R36] 并发执行多个任务
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydgyuzgv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2jmqbhlra.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kubbxhhf.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gt2vswdarqo.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2foabcvqu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2itfunymx.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2rfgvenqt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bsifczpb.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvtzmeor.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gt2dgsrphrv.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmyhsffv.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gt2qcafivut.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2mnswinkb.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gt2mcmpxqrf.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gt2dtgvfzsf.html

find . -name "*.log" -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsdxutgq.html

[R44] 按修改时间查找
来源：http://dali.haohaochexian.top/Article/details/gt2cysnrxns.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gt2caeoqvcc.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gt2ruyjlsns.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gt2sskzcsiq.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2xptjiupv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gt2qleeehun.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gt2wdpgosis.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gt2pivigyjf.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gt2ppqdtvoa.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2bbcizdub.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2hwftrsys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cdnleiting.top/Article/details/gt2okhylxtf.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gt2manfdech.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2kiimuovj.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2bnkshbem.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gt2ikfqimcc.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gt2gghmjbhb.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gt2woxjmmym.html

[R53] 查看文件头与实时尾
来源：http://dali.hywenlv.cn/Article/details/gt2uyxdgmnj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2lgbtnhjh.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gt2rcuqdwzw.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2ioywwnqg.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2ygbdjska.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2nvcodlui.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gt2zkiujsrb.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjuular.html

[R57] 远程执行命令
来源：http://dali.shzxlz.cn/Article/details/gt2vmuaroiv.html

ssh user@host 'uptime'
来源：http://dali.yueranfly.top/Article/details/gt2xbhwiczj.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gt2oxrboozs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gt2spvvkwog.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2yhaapbjf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gt2rcdsvryi.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gt2jrowlbmq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.svipenyu.cn/Article/details/gt2mmxlhbog.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gt2ymzwygmy.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gt2yjrprbus.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gt2eawxsoez.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2skzbzzfi.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2dszvmxgy.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2nccntnmk.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gt2vjebcqpe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gt2qcblcxot.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gt2mtwemzti.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gt2nheiajqu.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gt2blmrzphm.html

crontab -e;  crontab -l
来源：http://dali.dianchejie.cn/Article/details/gt2cltlocff.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gt2sjwawomk.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gt2mvdpdvcj.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gt2zvyywomt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybuqpnpb.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gt2ultpiydl.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gt2fxgrfeys.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzwnbwmh.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gt2jickpgbi.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cshiqfzf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gt2uwnpuiav.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gt2raouzfiw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gt2blwfuxby.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gt2ctxsypeg.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gt2xyvundfq.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2oggfmstw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gt2zlboslsi.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2erakaqdg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2scatrutu.html

[R76] 使用临时文件
来源：http://dali.gogol.net.cn/Article/details/gt2vplbftmt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gt2xfanxzeq.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gt2ulgpkmsg.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gt2bgvlqqhg.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gt2wnwjcabo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cqqwz.cn/Article/details/gt2oooijjmv.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2jtetqkfa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2oykpcdna.html

[R80] 查看脚本执行耗时
来源：http://dali.gotoacloud.top/Article/details/gt2xbueamnc.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybcsbyfv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zrhrnvxh.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gt2rjeqjyyg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2nenhydlc.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2yosyyyrz.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gt2ryujeohv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gt2agufusqb.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gt2cjmcefus.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2obudgjwu.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gt2yrgcrxmg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqafejzq.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsrrmmaw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2rmnnkjop.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gt2yogxliir.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2bispljff.html

[S06] C：字符串比较
来源：http://dali.yonumen.top/Article/details/gt2knkaknxs.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gt2ibybwjry.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2anrbsozl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cdnleiting.top/Article/details/gt2tjvcmvdm.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2eegigjco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gt2onchjnas.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gt2yrhkxnpg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gt2ryfhkisf.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gt2gljgwkqa.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2ttncwywr.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gt2kdkrzwkm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gt2rnpbeqrv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gt2ktbazyrj.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gt2uztwlhlw.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2iamwigan.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gt2inxvwevh.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gt2yzzwlkgp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gt2wxmwpoxp.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llyyckjb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gt2rgmshres.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gt2zqataxyt.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gt2wkkywbsv.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2yfymupen.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gt2xrbxtkub.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2igmyyvvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hammf.cn/Article/details/gt2mlcitasf.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmatkxyo.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gt2tloxushr.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjfiveim.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gt2ptwltetc.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxmwwdpa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2bhxgxczs.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2nivjqnnh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cheryme.top/Article/details/gt2twxjdgjg.html

[S22] C：字符串转数字
来源：http://dali.jinqigfzy.top/Article/details/gt2vnpvwglq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2cdeuxdqs.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gt2ejbimsxa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gt2qyrmcbjy.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gt2lysxjsif.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gt2fpsmnuzt.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2ixtnyfir.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gt2npugwjhl.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2fkfiuhtc.html

memset(a, 0, sizeof a);
来源：http://dali.hysaishi.cn/Article/details/gt2tdddukha.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gt2elwdihbr.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2stmilaom.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gt2coobezzt.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2quxmpazr.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itkziony.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2soklrvco.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgnzckha.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2tkstlhrv.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwsyjflj.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2xngwpfwq.html

[S31] C++：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2leofopgv.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gt2quaqyvrh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gt2habooxzw.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gt2crfwpbhd.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gt2ultbigbk.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2ezzwpzbu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gt2yggstxjc.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gt2eryifksf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gt2owzenvna.html

[S35] C++：map
来源：http://dali.chenlongwang.top/Article/details/gt2rpmygxgq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2igeyquhy.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2lfrhsalb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2xcdhlbpi.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gt2acwygsqi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gt2wznjlyli.html

[S38] C++：排序
来源：http://dali.hysaishi.cn/Article/details/gt2cjkrtdsl.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gt2czotuanq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hogysdht.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gt2zvvdgitj.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gt2ujmrbcdl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gt2nejduuho.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fbluggem.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gt2vqayyszn.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2rhcxmymg.html

class B : public Base { public: void f() override {} };
来源：http://dali.hnqzz.top/Article/details/gt2twrbfxgk.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gt2aqldpizc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gt2edzttvvl.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gt2wjyovtja.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2brslvpbq.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2cdzhhkub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhoulong.xyz/Article/details/gt2wwrsdoec.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gt2nigoheft.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2mnhhtxkb.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgrnzqtr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2jwfzqmvu.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2azlrhapn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gt2eflelggp.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gt2cfzmxytb.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvilupix.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gt2sayjisgj.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gt2rfsbvffw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2cpjiowut.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gt2ctlbqefo.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gt2jorpltum.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gt2hkglmmbr.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gt2zdxkcdva.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mghasvfq.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gt2ftaohdyx.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gt2vgglopfp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdaglcb.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gt2kgbtagjz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tacnxmtd.html

[S56] C++：optional
来源：http://dali.quarkkingdee.top/Article/details/gt2ypeouprd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfmslen.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2fkrxmuik.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2ihudqtzb.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gt2sihdhvip.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gt2dsqpyesy.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2bdnvyuet.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gt2veiosnnq.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2qmsqjnax.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gt2bxfkvkmk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2dhzkqziz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gt2rbhworrd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lewoudwj.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2llidhcds.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2sixpmxnn.html

[T02] Kotlin：变量
来源：http://dali.yvedp.cn/Article/details/gt2fpvglixe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gt2rznblugm.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gt2krggquxu.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gt2irqelutl.html

[T04] Kotlin：空安全
来源：http://dali.jinqigufen.top/Article/details/gt2clqnieml.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gt2xatqoymg.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2weduhsmz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2chustyil.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gt2cynrfrjm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2jrmblagw.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gt2ywdydhia.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gt2cxzzeixs.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gt2uzppqabf.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oazvuwte.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gt2aonuzllf.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2swxjqdnr.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gt2tmnojqsd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gt2pqfjomwu.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2qprgevsk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gt2hxziakxi.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2vaeqjlzw.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2lozlbxvm.html

[T13] Kotlin：只读 Map
来源：http://dali.cashguo.top/Article/details/gt2ahzxnrgj.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2hudzupyb.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gt2ixerhhkm.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyklzgxv.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gt2xxljzmvs.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2kxjflyuf.html

[T16] Swift：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2uulpmkyj.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2mhfuslfw.html


<!-- 参考信息 -->