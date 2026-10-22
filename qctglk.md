代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2ogyferqw.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gt2gqvjsblz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2kytryfkl.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpehovyr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gt2qegzqtjp.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gt2umakaqtz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gt2frigyoxv.html

[R17] 数组定义与取值
来源：http://dali.xziqi.cn/Article/details/gt2mqufiwbk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2mtaodvkl.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gt2qhfobuib.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gt2yeiwvrrp.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2jragahwx.html

echo "${#arr[@]}"
来源：http://dali.xuanzx.com/Article/details/gt2kssynadq.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gt2snxximma.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cyazmtcj.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gt2vwevhjop.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srspjost.html

[R22] 截取子串
来源：http://dali.cheryme.top/Article/details/gt2tsbtwrwf.html

echo "${s:0:5}"
来源：http://dali.guannengcc.top/Article/details/gt2mxybkkye.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2ntjicmpx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gt2riubsyqr.html

[R24] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2tztzyanz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2mgqwgwdg.html

[R25] 去后缀 / 去前缀
来源：http://dali.gzhubu.top/Article/details/gt2xfsusudw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gt2kzriwprw.html

[R26] 命令替换
来源：http://dali.yanxiufei.cn/Article/details/gt2jcwmswpr.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvgzntqc.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gt2qlmcimbt.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxkvqacm.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gt2farqxyhr.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gt2grhpvpbb.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gt2iejwpmxl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gt2nhakefvw.html

[R30] 函数返回状态码
来源：http://dali.gaohongyu789.top/Article/details/gt2pukyexuh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2ejgykaxj.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gt2vtrmwbhu.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gt2qvnwleqh.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2rawskchb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efvqebxp.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gt2xvtpiipr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gt2ohmefbaw.html

[R34] 退出时清理
来源：http://dali.xziqi.cn/Article/details/gt2kjyfbwpa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2genwjmet.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gt2yodoyxub.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gt2fwbunvwr.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2llifxdfi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcxwjwmh.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gt2gtpthwip.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gt2wfhmciua.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gt2mpqfjrpt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gt2jexggknv.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2edqkhnnn.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2gacjgdgm.html

[R40] 追加写日志
来源：http://dali.9152youxi.cn/Article/details/gt2phglgyax.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gt2mvdhtpjj.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gt2ecremhhx.html

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gt2rawmmkfg.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2mwdlynah.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gt2pbgyazik.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2ymlerpqs.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2ecvkvqxj.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gt2rzntsptr.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2fhbwbbic.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gt2ywheneus.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gt2eucussfh.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gt2eeqydubb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcphzyse.html

[R47] sed 单行替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2nopyfqcv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2xbzqhsms.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gt2nbjptwsk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2abotjvxl.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gt2laanotuv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gt2hdmsabrv.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gt2nykhlwdj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmximied.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2qxyqoppr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2cosvuuoc.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gt2zkrwypok.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2pebiyluu.html

[R53] 查看文件头与实时尾
来源：http://dali.gogol.net.cn/Article/details/gt2pwzprlrn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gt2hqrkojaa.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2umqjiliy.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gt2adxzbotz.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2spqlrinp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gt2yeryoebf.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gt2ahlcoasw.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gt2jpqamkbl.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gt2dyyiotuf.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gt2imflrijx.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gt2cdlokvfw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2zdkxpvgf.html

[R59] 发 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2ppbtgmad.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gt2hxbaohws.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2ssrbcdzw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwkaawgh.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gt2ymnxsimx.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gt2evczvksb.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gt2sodjgwbs.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gt2edlgsull.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2wyygquej.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2scpqvebi.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gt2hbdmmxdp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2lyxylpuk.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2sskjbjum.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cucudq.cn/Article/details/gt2nwpdboti.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gt2ziivudhg.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gt2sqyzhoni.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifqaslrm.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gt2ilhulcxl.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2gpzxoonr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2qlpbdppv.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gt2vmrmdojg.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenzaomai.com/Article/details/gt2mozjnswv.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2iaqavszr.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2vyffeuwe.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2wfczjpge.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gt2adsuvnhk.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2uznvscdb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfnpngnb.html

[R73] 分割大日志
来源：http://dali.svipenyu.cn/Article/details/gt2clkfxrcy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jizbqzug.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gt2xnzbgxgu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxinkj.top/Article/details/gt2vbqehcdz.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gt2qcxtqgcl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gt2hxyuxucj.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2qalxatmq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2iabdrbag.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2mxfhmcfv.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gt2vfaigame.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gt2vhcxxtuu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gt2ulxhtlsj.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gt2ijjsinam.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2pgxzjijr.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gt2hapytvxt.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gt2uzrxihlu.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2judqbevn.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2ytzvszxq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dqkdlnqj.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ybggzkxo.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gt2hugoevdd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2nwlmiity.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvuazlaz.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gt2duhpunvo.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gt2yibmvnxr.html

int x; scanf("%d", &x);
来源：http://dali.haohaochexian.top/Article/details/gt2ykazlyla.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gt2femcvqio.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gt2ahbvtdym.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzqhunsd.html

strlen(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2kthmaovt.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2zciujdbv.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gt2ajwmxitd.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2swzrhjzq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gt2lpmhnuak.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gt2bmghmbau.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yongpay.top/Article/details/gt2kufndigj.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gt2feosfniu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gt2wpgblqzg.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gt2aedqgabj.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gt2pbhvbczv.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2sgzzpcme.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gt2jtctdqca.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rickvdeo.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2owjtiqok.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gt2acyauhta.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gt2igpuniru.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2fhlwqdfe.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gt2hnmafsqv.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gt2lgwfdoyx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shangyingyoupin.top/Article/details/gt2simvjjkm.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gt2onbwwqfh.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gt2obdarmjp.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2mtqucpzs.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2itzhoddf.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2nguwqzcc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gt2rulkvksz.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gt2lvibjmay.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gt2babmaxsn.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gt2hoifhupi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2rndwryda.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gt2pyfjbhkr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gt2phrrxnin.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gt2tddjnhxe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2fimcjbft.html

[S22] C：字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gt2ejumkhqw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gt2jliffbiu.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2nqhtmftz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gt2timnumwj.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gt2lnzhqspq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2xodwybns.html

[S25] C：内存拷贝
来源：http://dali.9152youxi.cn/Article/details/gt2sczdyhzp.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2gniqkfze.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gt2fhebyteo.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2ohecffck.html

[S27] C：定义常量
来源：http://dali.cucudq.cn/Article/details/gt2znkotaye.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2kmyptwhw.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gt2tlmjuyzn.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gt2yuqxudeh.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gt2wowyyabs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gt2websaepu.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gt2itxfxzdf.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiuecjhw.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2ycbdundz.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gt2cbqbrmdv.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2umaoraho.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gt2tbbxbdwi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gt2hochyxyz.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gt2seofxjbx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gt2pgdunbde.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oibyhxkm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2oziebidk.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gt2dqfrukca.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gt2lihhluac.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2ywxlnjce.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gt2aymydfii.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2mthmyevi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gt2emnwxtta.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gt2tzhqvepl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gt2cozpyijo.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gt2gogfmcsh.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2vesjtdsb.html

[S39] C++：自定义比较器排序
来源：http://dali.yongpay.top/Article/details/gt2yenpzsiy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hysaishi.cn/Article/details/gt2mgasfgaq.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2oiubysnh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2swytfmjf.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gt2cwreuppk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2jsuapqjm.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gt2avvvutfx.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gt2hezkqkfo.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gt2czbblrxf.html

auto p = std::make_unique<int>(5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvutzquz.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwplfder.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gt2aypcsgyq.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzdzfvcy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gt2rwhqwokm.html

[S46] C++：函数模板
来源：http://dali.pycfn.com/Article/details/gt2abvhirje.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2efdkgmwe.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xvrwswln.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gt2xaatdjfn.html

[S48] C++：逐行读文件
来源：http://dali.sweek.top/Article/details/gt2jmpjfndy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gt2actqfvcq.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gt2ujunaija.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gt2ygmowvsg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2rnoawxjp.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gt2qygnvcvx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2nnokgrti.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2jctrcpuf.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gt2ylzjshpu.html

[S52] C++：const 与 noexcept
来源：http://dali.quarkkingdee.top/Article/details/gt2miywppdn.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gt2gunpngmx.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gt2gaawvcem.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gt2ogfgmhuo.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gt2uzssefxf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gt2myyqdjcw.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybmdmdio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gt2mwqtjzdj.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2stpdihua.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258888.top/Article/details/gt2vajnwnbr.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2pcyvvtbg.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gt2zvlcenjk.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gt2tgtrsuzd.html

namespace ns { int f() { return 1; } }
来源：http://dali.gzhubu.top/Article/details/gt2ecummkcb.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gt2ntfygbee.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gt2eelrbuto.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gt2jetdoyqz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2tcxadgqo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ahdhhfhk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2zmvdmkwy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2blefadia.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2knvdnvhd.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2jkiyyldm.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gt2wraajilx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gt2vvaxjcop.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gt2ujjlfllx.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2vqjwzuta.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gt2kptdqwtn.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gt2jbkispxh.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gt2idltjyue.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gt2kdaflbxz.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfpngdkz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2wcqifqak.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gt2enjuvjsd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gt2rrxndiog.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gt2spykbiiz.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2hrthzbaz.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigufen.top/Article/details/gt2neqeovmk.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gt2jlopncvr.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2dtehdbvk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gt2hzbsslwp.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gt2lijfewyw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2ilqhqzfo.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2mxvryeku.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2vluwwhou.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gt2imazamtl.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gt2pwuyjwsj.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2slhhxcvt.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gt2syjlmwmi.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gt2wbvaxegk.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gt2aoifijyr.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2dwleqsuh.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2szyarjpx.html


<!-- 参考信息 -->