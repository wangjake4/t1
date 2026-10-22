代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gt2eqszgwvk.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2idqhduyq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2bxvuyzsk.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gt2nmzdcoxf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2sggitaem.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gt2ykpmjtag.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gt2ejoiekyq.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gt2uttnfewe.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gt2umgifrrl.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gt2tolbtgvq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2gwzxwnke.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2bybcrxsl.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gt2ywikkcuu.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzslhevu.html

echo "${s:0:5}"
来源：http://dali.havefunace.top/Article/details/gt2puadtamn.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2sxismpiu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tanke756.top/Article/details/gt2hzxsulzb.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gt2dasusjgc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gt2mviikyku.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gt2ftxfsrbg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbsptzih.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gt2cnzqqpth.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gt2qbvfcjaq.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gt2acsxoyac.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2sgqpytkq.html

[R28] 浮点运算
来源：http://dali.wangshuangyany.cn/Article/details/gt2zegovgvc.html

echo "scale=2; 10/3" | bc
来源：http://dali.hammf.cn/Article/details/gt2bgmqtaoc.html

[R29] 定义函数
来源：http://dali.ydzc1.top/Article/details/gt2akgzlxvn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gt2xmcnpmjv.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2uuvfjbyx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2owbdgbsi.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlltytpe.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gt2nwafogdt.html

[R32] 参数个数校验
来源：http://dali.hnqzz.top/Article/details/gt2etzawgtj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gt2lsgfcrcm.html

[R33] 捕获错误并提示行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2cmhafbbj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2yhxqsbrv.html

[R34] 退出时清理
来源：http://dali.mhx1999.top/Article/details/gt2yolsieuy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2lqljnmek.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gt2tdxuhryl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2ypwnzgsr.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gt2yrdszcvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omsmukfk.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gt2rxbmhfud.html

files=$(ls -1)
来源：http://dali.ppjwa.cn/Article/details/gt2dyucidek.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gt2jhneyoht.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuanzx.com/Article/details/gt2ehwvejep.html

[R39] 重定向标准输出与错误
来源：http://dali.yj202588.top/Article/details/gt2phyjyzpn.html

cmd > out.log 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mmhmugwb.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gt2livwrqlq.html

echo "log" >> out.log
来源：http://dali.aibaodan.cn/Article/details/gt2qwispbzf.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gt2blqfaybu.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2qouvkpzs.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2cggtmwuk.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2nltjixqy.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2zmymtghr.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gt2lryexkko.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gt2mmfjmvfs.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sbpzsvde.html

[R45] 批量删除
来源：http://dali.svipenyu.cn/Article/details/gt2suyuoree.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gt2paleqxpg.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gt2wldtnzcg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gt2dwatacce.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onwjhdje.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2dewukohp.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gt2rxcismnb.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2ssepewnh.html

[R49] awk 带条件
来源：http://dali.nwbrower.top/Article/details/gt2waqnyidk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gt2shnrmdvj.html

[R50] awk 求和
来源：http://dali.yanxiufei.cn/Article/details/gt2yhtuczbr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2vwojmpch.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gt2ahljqqtn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2bnclkqnb.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gt2pnczlzpl.html

wc -l a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2jbmtucmy.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gt2mxmoxgud.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxuanxn.top/Article/details/gt2jvdyesaz.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gt2gfrykjov.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gt2kvwerleg.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gt2ppxbhlbx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2uwdpgjrq.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gt2tuzgqpdp.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2vgmhxgno.html

[R57] 远程执行命令
来源：http://dali.zycfv.cn/Article/details/gt2cnntvwzr.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkvorkuj.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gt2iysbtybl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2fhztshtw.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2sklcztoh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gt2erexhdjt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2giqusrwo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gt2kxnqyhde.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmkzfand.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2ubcwdkmv.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gt2xsearjgu.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlmsrzrc.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gt2fzhkabuz.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gt2irhccudh.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2bjpzgadk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2srxvkshc.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gt2bsqyqubl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gt2uvoemwef.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gt2kzvnzpfr.html

crontab -e;  crontab -l
来源：http://dali.jqgufenzy.top/Article/details/gt2ksxwxyvl.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gt2pgemoqbv.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gt2tugttsrs.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gt2kndxqlpk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxrdhxao.html

[R69] 生成随机密码
来源：http://dali.nwbrower.top/Article/details/gt2lolxrsvd.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gt2joblwyog.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gt2voiwnmqt.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gt2fkusxucj.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gt2yvzljtbn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gt2txwmoovs.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gt2fktwoytj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2cpzcxhyo.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gt2kggsqguy.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gt2woibyyaw.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gt2xbzurnse.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2btgdyplg.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gt2deytfatt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gt2pxciiwoz.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gt2iegejpxi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2bumekwue.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2hmveyncq.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gt2qxwtlxwz.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gt2xaimxqwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gt2pcvigvko.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gt2adrhqpez.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gt2gtlttymu.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gt2cnnjrdyp.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gt2hmhcneal.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2brnbebxf.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gt2aeywsxay.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2oqiijorv.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2ormoosrc.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gt2khkhznob.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gt2yqoyfblp.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2lsxbylse.html

int a = 10; printf("%d\n", a);
来源：http://dali.tian-w.cn/Article/details/gt2vacrsxtx.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gt2wsbpxmad.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gt2dljhgyno.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gt2atomazet.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gt2hqhtuysz.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2edjcelur.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2tnrucair.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2wbcsudxk.html

strcmp(a, b) == 0
来源：http://dali.jqgufenzy.top/Article/details/gt2fraefwza.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2jaksobqj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rychkbtl.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqbbbyjy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2aajkfyhg.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gt2rswextph.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.quarkkingdee.top/Article/details/gt2bkuczwsj.html

[S10] C：指针与解引用
来源：http://dali.jqgfzy.top/Article/details/gt2spqducio.html

int *p = &a;  *p = 5;
来源：http://dali.havefunace.top/Article/details/gt2bijkhzma.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkvdujw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gt2iweumwbg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gt2rtnpszjb.html

fclose(f);
来源：http://dali.iojbl.cn/Article/details/gt2nmfjivyy.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gt2ddojxems.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyilqsmp.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vilfaaju.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gt2qkojiqjj.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2yajwsbuy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gt2zwewyyzd.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2hoazvlfk.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gt2jszysrtn.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gt2sawuspco.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gt2qhexbgmv.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2faesmzay.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gt2tmpukrjd.html

[S18] C：命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2qcnstmsz.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2hmufmqpi.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2weppqylu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gt2vssmxfpw.html

[S20] C：二分查找
来源：http://dali.yuanzhike.top/Article/details/gt2yvopzprv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2gywyjtep.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2lhdtfhkc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gt2onxarbhk.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gt2zmhokoqk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gt2eudprncz.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvigvvkl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iliipkgo.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2psixjjoe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gt2pgscbigg.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjynkecf.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gt2mtzoyrdo.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gt2anlwwpgc.html

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eanhpwnw.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2fttmhlvn.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gt2mhfqhzbw.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gt2zvfpbjvj.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gt2wthpzmvj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2asvckrsb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgfzy.top/Article/details/gt2hezobchq.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gt2fetbzbjq.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gt2ilayjcmu.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2vfwzyukj.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2qhpiyltb.html

[S31] C++：Hello World
来源：http://dali.316326.xyz/Article/details/gt2uqculuzg.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2ljgpkqbl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gt2kzxnfkjv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2prxkmofo.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxinkj.top/Article/details/gt2fedvofhy.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gt2entjfjqm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gt2hufgdcct.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gt2dazbtwzo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gt2isjbxjgk.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2pqzuwrlt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2mnrlwtjc.html

[S36] C++：unordered_map
来源：http://dali.hywenlv.cn/Article/details/gt2pveoscdc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2qrsjpsxd.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2dqcpljah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gt2psdbekmb.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxmtffsg.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gt2keawpvvt.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gt2hgcnogko.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gt2jsxevysd.html

[S40] C++：查找元素
来源：http://dali.hnxiangtu.top/Article/details/gt2vgkgfmuo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gt2mlykrlkc.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gt2dhlgxbtv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtqmwgue.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vluvhhxj.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gt2dpyfrtaq.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2trxlmzts.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gt2sohsxxar.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gt2dzhcgtwc.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gt2gjzhtlzi.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjuhztmf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwaklewh.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gt2srlppvon.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2scppiobg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2qfwxisqy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gt2sdbigobl.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2moteimzv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hfpthk.cn/Article/details/gt2wxalhgue.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2siujgorz.html

[S49] C++：写文件
来源：http://dali.andypj.xyz/Article/details/gt2togreujc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gt2uwryssrw.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibbpffsi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2zpkjdxpr.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gt2afwtaqin.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gt2swyrlxgm.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gt2dpbfnhhv.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gt2rdeoeijs.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2oddbzqrg.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2fdbsohpl.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gt2xvoefoqj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gt2ulizphjz.html

[S55] C++：结构化绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2kdkcnjbs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gt2nmjztbwv.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gt2isrbcrtc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gt2kffutzrr.html

[S57] C++：编译期常量
来源：http://dali.hongshengwenyu.top/Article/details/gt2kbzpcthi.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gt2vmyqgotw.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gt2hfyencen.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gt2ujbiutew.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gt2bbdnfiqt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gt2dgilzlhm.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2pjnocean.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usaijead.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2wutbepsk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2offxvsyt.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2lsasvlgw.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2jbulxfsc.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2slmdojjj.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gt2mfkhphmh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gt2ulgkintp.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2mvhebejp.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rgiaocmn.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gt2cakgrbxp.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gt2njrnjqrf.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gt2kirwprmg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2ivkmgfdq.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2mxnjujvu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gzhubu.top/Article/details/gt2nsthlkwt.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2arpmtpai.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2viiugwmw.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2kftbyvxg.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gt2qtemkdte.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gt2sageodtl.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gt2idubdajg.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gt2fgxuhfgn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigfzy.top/Article/details/gt2pwypynpx.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gt2bltfcovb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2exharokm.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtdbwzrt.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2gnwamzpn.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gt2pplwhowi.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gt2kujlulxh.html

[T14] Kotlin：循环
来源：http://dali.hammf.cn/Article/details/gt2vzaootmt.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gt2kfmknsyw.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gt2waewxcqy.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gt2pzwfzncg.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2znxnmswg.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2cjxxbezn.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gt2whnpjynn.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2gtpdayem.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2altodton.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gt2lcxyiwzx.html


<!-- 参考信息 -->