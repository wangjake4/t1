代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.redwolf501.top/Article/details/gt2txjwppwe.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2jzeoppxy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gt2jnjcfycf.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2huokwlkj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gt2uvhrgduj.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlyjagch.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gt2ijkpixwz.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2xyjquvuf.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gt2tfursbfl.html

[R28] 浮点运算
来源：http://dali.dashuyun.cn/Article/details/gt2dgwoleiq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhoulong.xyz/Article/details/gt2xuiflche.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2kzxlanzo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gt2bctmrhic.html

[R30] 函数返回状态码
来源：http://dali.chenzaomai.com/Article/details/gt2xnunntot.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxhaufev.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2vswhesmm.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkrtcuon.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gt2ksneebti.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gt2wnjspbue.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gt2xmvkkslo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gt2iejixtcb.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gt2gyilmkyk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztjpjixy.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gt2mpuzgqgf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfmheigy.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gt2xeymuzjz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2ibncvytp.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmzlltio.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gt2fessnhfb.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gt2vdrsmhpc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gt2bjkvddnx.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gt2xkwoadhz.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2zeaafimu.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2mclbpflb.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gt2merntmab.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vckgetgu.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2fuvojmjo.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxklqwif.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2mdsrveua.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2wxcwxgkk.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gt2ktsiiwqv.html

[R44] 按修改时间查找
来源：http://dali.shuidangran.top/Article/details/gt2gocfifwr.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gt2wrjtwybm.html

[R45] 批量删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxzccwfx.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gt2dbpjflau.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2laqeunmp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gt2bwsfjyqe.html

[R47] sed 单行替换
来源：http://dali.mhx1999.top/Article/details/gt2zjdjmmzn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2idtkarim.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gt2jooyiyty.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2lmavggfp.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gt2rbcvibke.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gt2jfclxbyj.html

[R50] awk 求和
来源：http://dali.havefunace.top/Article/details/gt2trvcwtus.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tanke756.top/Article/details/gt2azegdsuj.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2cnqdxxjh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gt2dciejmmr.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gt2mabhmtbe.html

wc -l a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2vvxcymyo.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gt2piuatmvd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2hfnweiis.html

[R54] 比较两个文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgujtbnv.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gt2mbbmdgbb.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gt2hemtvfhs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sxryk.cn/Article/details/gt2qlldksss.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gt2rikplkhu.html

scp file user@host:/path/
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dmcirrvx.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gt2kwbymvyj.html

ssh user@host 'uptime'
来源：http://dali.yanxiufei.cn/Article/details/gt2tantepwm.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gt2bvcaiort.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gt2lpbdomql.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gt2mnuxvoqs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gt2uwufzdta.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gt2mldcfgti.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2yngdtdxk.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gt2eanuyfuq.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gt2cnngpofw.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gt2lootdspc.html

du -ah . | sort -rh | head -10
来源：http://dali.hnxiangtu.top/Article/details/gt2uemtdvgd.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvwgciep.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gt2mewqnjne.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gt2mukklzic.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gt2ibodbjcx.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2flnekqfd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2azycydrr.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gt2esofnabv.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gt2gchqwwow.html

[R67] 生成随机十六进制串
来源：http://dali.iojbl.cn/Article/details/gt2qucxsuxh.html

openssl rand -hex 16
来源：http://dali.quarkkingdee.top/Article/details/gt2iahgmkri.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukecghlt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtmwvxkw.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vecejuzi.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gt2nuowveup.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gt2dpldzdqt.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2rcorxodq.html

[R71] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2eftlrqwo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2tlbfgqyv.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2seahuucg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gt2eeokqkqy.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gt2ghssoseh.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gt2yvdlunfa.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2tuwdhlnf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppflwbtf.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gt2btibqljv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2cxasawie.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2bkvgocty.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2ijwjrkiz.html

[R77] 读取用户输入
来源：http://dali.hnxiangtu.top/Article/details/gt2aykoqash.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpnbfriz.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gt2fmlzbndc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2fryfyzkw.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2ruivfjhh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gt2njjkhyqf.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2okajjybe.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gt2yjptrmxc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2putrbrcu.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gt2ufrgjulx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xtphuzwd.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2dzqhdhpx.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wffqnlio.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gt2gfexrimb.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2ndhpikkc.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gt2mcmtltgt.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2fsnurfeu.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kknoapsd.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gt2gigudwee.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2jrojcmog.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndmeqoaf.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2ncaebbji.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2oirnmbpb.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gt2rodhewyw.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gt2eoyvenkz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gt2dkjiepzp.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gt2dfabqtru.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gt2jnxwyoxt.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2rqzoonkn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2oiiijeso.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gt2dejxcvbm.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2rprekhjg.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2snbsdjnj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2kpdsoaci.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gt2juawxzjt.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2rmeivzsp.html

[S12] C：写文件
来源：http://dali.mhx1999.top/Article/details/gt2rtkrvaao.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gt2jqnldkkt.html

[S13] C：宏定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnovpbaw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gt2cxshobck.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gt2ltmfhiwx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gt2ndsofkiq.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2qdgkrvma.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gt2xdgcvcgn.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gt2fjriwunx.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gt2rnxkehos.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gt2zwwskoge.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gt2snxhmtfx.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xswekclr.html

int main(int argc, char **argv)
来源：http://dali.yj20258.top/Article/details/gt2litnvwwr.html

[S19] C：快速排序
来源：http://dali.jqgfzy.top/Article/details/gt2qbulzvow.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gt2dfpnhklg.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gt2rufqqnsd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2eitowjll.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gt2tdchixzc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daria6918.cn/Article/details/gt2kdtauehv.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gt2tpxgdxmf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shzxlz.cn/Article/details/gt2irhhoyus.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gt2fsqntnru.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gt2goezvqqc.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2qqtyyjhi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gt2tvbfdtsz.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gt2ffyvcgjp.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2bsvloebu.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdxbzemn.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gt2zsueqapz.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2tgrnlhux.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2hyvkwpbc.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzbiilac.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2ciagsiap.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gt2kipfrobr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gt2qbyebvcu.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2htptsjpj.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gt2ckdfypdi.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gt2iqewgqmk.html

#endif
来源：http://dali.ppjwa.cn/Article/details/gt2ppfzbsuu.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2fpedoijq.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gt2jjncmwsv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2jrkdhydy.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ygvhbbsa.html

std::string s = "hi";  s += "!";
来源：http://dali.wangshuangyany.cn/Article/details/gt2judfvaqg.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gt2otxskuux.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258888.top/Article/details/gt2gsekdmsu.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gt2ilovuryh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2mtrmmonm.html

[S35] C++：map
来源：http://dali.guowangkeji.top/Article/details/gt2mdkfjrsx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfgwyubc.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gt2sfadibgl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2trourmgl.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gt2swigzycm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gt2wibmdsyr.html

[S38] C++：排序
来源：http://dali.tanke756.top/Article/details/gt2jdigvtkp.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gt2bcrddsqe.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2akkwqwgo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwmdtraq.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gt2jhbshfoh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gt2efvyfknx.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gt2kmualebd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gt2fslrbvqf.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikzlfwtf.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gt2wobczrgl.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gt2upeycrvi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uijybach.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2ucblgvbm.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gt2yjdugjfe.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2szjafomg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gt2opqbsows.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2zrplsawi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2oqlqfibr.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gt2mhcifaza.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2ouippggd.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2pmkjfsto.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cdnleiting.top/Article/details/gt2aksdtgah.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2iqcdlaym.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gt2xeztoxwm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gt2fifxfscn.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gt2zkwbuadi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2nymowtrf.html

[S51] C++：显式类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2bovoadzl.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gt2ggenaksj.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gt2oqsuopml.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gt2ynkywyax.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfyrgxjz.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2czfixttb.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gt2dpcywwwq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gt2kztflxtu.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gt2lhmpgyfr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2tyrewalz.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2ifywaeia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2garmzdlo.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2mwrnimlp.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gt2hmffxfpj.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2npasvmvf.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2duvuvbei.html

[S59] C++：静态断言
来源：http://dali.cheryme.top/Article/details/gt2wppaytrk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gt2iabwadpz.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2kawseevy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2uvgqwhjc.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpvgrauw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2kyguphkf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gsjomttr.html

[T01] Kotlin：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2meyxdbix.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gt2kiknxbtj.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2nuiecfkz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gt2khxzdmlm.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gt2optdggnc.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gt2pbukrpgt.html

[T04] Kotlin：空安全
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okaoiair.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2hiqmffyh.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gt2synpogoy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2sejylqtq.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gt2urguztep.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2htsyikox.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2einfftvu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuanzx.com/Article/details/gt2rdamatxu.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gt2yscsxykk.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2nrudevxy.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gt2xotwskok.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gt2qbivjdoq.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gt2unufvvzn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2lrpfwaww.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gt2ciyqahvo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mwcztjfg.html

[T12] Kotlin：解构声明
来源：http://dali.tanke756.top/Article/details/gt2hoipxzzd.html

val (a, b) = Pair(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2rppywrug.html

[T13] Kotlin：只读 Map
来源：http://dali.yuanzhike.top/Article/details/gt2cutmloup.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrcskvve.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2drudyusi.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gt2jjbzzcgq.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gt2hczppkjk.html

interface Shape { fun area(): Double }
来源：http://dali.cucudq.cn/Article/details/gt2drfdimgy.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2yerjqztt.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gt2zxdymgra.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2hioejfme.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jjtbghcs.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2tmduepgu.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gt2fbzcivfv.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gt2ylitfwzm.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gt2bwbueupj.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkdkaucu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gt2segzlvws.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2mphpftid.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gt2xolotudd.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gt2crpwszoq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gt2zbchpruh.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gt2hztynocp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2grlsyylo.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2ouebsfdg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2jwclxhbe.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2jyluhgtj.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gt2ftchjptg.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gt2pknobnvr.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gt2anjrtfas.html


<!-- 参考信息 -->