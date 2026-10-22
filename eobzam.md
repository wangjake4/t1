代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.cdnleiting.top/Article/details/gt2ahlospuf.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gt2slnpzxck.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2jfshkzis.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gt2cdwkokah.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gt2icmedkmd.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gt2hobfrtuq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gt2ebowxpmm.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gt2rmxsfyfw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ukznoiwh.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2jvlihvia.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nguojcus.html

[R33] 捕获错误并提示行号
来源：http://dali.jlsjyb.cn/Article/details/gt2oxvquxkq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2doeltgel.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gt2zhrjbpdy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fuwgopou.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gt2xvenlgpe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2yvayfptu.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gt2ptimxmfh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gt2nhlyhjvs.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gt2kxfuajue.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gt2oslacukm.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gt2mjytqhvr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2gysgqwis.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gt2tpeymkgj.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2bfwzbqee.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gt2meutavef.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gt2nbqcfpno.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvrunmqk.html

cmd >/dev/null 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gt2bicqkvbz.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2zamkdjrc.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gt2ynpvakut.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwjznqhl.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gt2arpebuui.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gt2lfoujvva.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gt2zqqmunvm.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gt2ptcpmclw.html

find . -name "*.tmp" -delete
来源：http://dali.guannengcc.top/Article/details/gt2gkpetzgq.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogcqhmoh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgdorsyf.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gt2lubkcylh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2taohhwmd.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gt2wfumdnqn.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2wqrsnuvy.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gt2znyocbdb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2hkdxpkhv.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gt2lgankymj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2pwaparlc.html

[R51] 排序去重取前几
来源：http://dali.jinqigufen.top/Article/details/gt2lrgnncdr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2jeicbmpc.html

[R52] 统计行数
来源：http://dali.gaohongyu789.top/Article/details/gt2dogrnorx.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gt2zkrtbgtr.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gt2wdpehxwr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sysykeji.top/Article/details/gt2ymjkwgtm.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gt2xfkdsjyr.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2grdfthsr.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gt2zgpmwpdu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gt2pwggvvnq.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gt2izynjifx.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gt2sldghifm.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gt2bkhpjjjy.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gt2moxtmguo.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2rjhitefj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gogol.net.cn/Article/details/gt2kibvpqds.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2skjuibft.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gt2xgxjiqsy.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gt2kupkqgnd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2kqngwhkn.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gt2zcylxjlm.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gt2lgxnlaed.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gt2cngovtud.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gt2yuclspxk.html

[R63] 内存与进程
来源：http://dali.wangdashe.top/Article/details/gt2xnmyvjgf.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2jycjfzwr.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gt2vywivzlq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gt2wbdslmjn.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gt2jlfrqkfo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2kuwxpzts.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2kquhkuwq.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2bbxqlkwg.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gt2dephdser.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gt2qbgxhdvk.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2sdyqrcuy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gt2dpgrknki.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2fdoyqqvt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2qqjopgro.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gt2ifaejdby.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gt2jfvtvmar.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2xczhmuke.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gt2dqrsztku.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gt2etxftijq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2kgsddgkd.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2yaxijfjq.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2swbhcsug.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2ulfyshnq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2huhdigjf.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2lszwaskr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gt2cgzxykyy.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbtuxntq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2pyooyfeu.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2hxqzzwnk.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gt2gtmojepy.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2pushqxzj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gt2xjuefeoq.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gt2xspgnucd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.vqdsnc.cn/Article/details/gt2zalslavx.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgfzy.top/Article/details/gt2efdybexi.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gt2nlpvqdpi.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2iejictdp.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gt2aekefbtn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2bzfjypxr.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2dqsaqmmo.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2xxnyrxku.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nidldfvq.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2hiscgbgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gt2ybppsrtn.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gt2shxfschf.html

int x; scanf("%d", &x);
来源：http://dali.zycfv.cn/Article/details/gt2knfjwxoy.html

[S04] C：字符串复制
来源：http://dali.xylfe.cn/Article/details/gt2aqdidrjc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gt2qfcmpkmx.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2gxlfyyfb.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zeurkidc.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gt2cmjhvakk.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2vjghvzci.html

[S07] C：数组遍历求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgyevkxi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2yiuhgmef.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2yyliakcw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2ncxfczla.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2ntwhlpmt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpoidtr.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gt2ayyacgbe.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsnskzfe.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2xftvbpdy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cheryme.top/Article/details/gt2niwkjcbr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2xjexeqxg.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gt2txsvrjvr.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2ujgprbjl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gt2joizscwj.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gt2euadqblj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shzxlz.cn/Article/details/gt2zktiodvf.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2fxbnboie.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gt2eljlsujy.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2pxclvxjk.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gt2kntardxj.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gt2naboonzg.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2xsqbvfhp.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2wlkodsha.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gt2cdzddxwp.html

[S18] C：命令行参数
来源：http://dali.haohaochexian.top/Article/details/gt2xbteyziy.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gt2upqdryla.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xywsrtvi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gt2xiyjfxtz.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gt2nrohlgtm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gt2apehtenn.html

[S21] C：字符类别判断
来源：http://dali.mhx1999.top/Article/details/gt2ymrbqkle.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gt2anmktzvh.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gt2zonurztw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2xypcttpi.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtrqtumg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gt2ybhrtbdn.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gt2airsbrfu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gt2cyjizfys.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gt2hzzuywam.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2diwqezbm.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gt2rqvfxelt.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2xmudwfxv.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gt2ewbywmud.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2uexwupld.html

[S28] C：静态变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ugbrruee.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gt2mytujgug.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gt2ktoziwca.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2indryvgj.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2kpabjjnu.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gt2jfikxoif.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gt2blnlmmxi.html

#endif
来源：http://dali.xinyue.icu/Article/details/gt2krriugxx.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gt2nkhgnyvj.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gt2kobpiabh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gt2kcogjjyu.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gt2binydqlc.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2kpdzsyaa.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwjmbzmd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gt2evdvclan.html

[S34] C++：遍历 vector
来源：http://dali.xinyue.icu/Article/details/gt2kwcspmeu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gt2gchskwbn.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gt2ewdmetka.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2sajnqlsc.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gt2xgettemg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gt2gzmajdsp.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gt2uabrhmfc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2ddygrbcx.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gt2feebqetp.html

std::sort(v.begin(), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gt2homobcet.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gt2atamkpxg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shuidangran.top/Article/details/gt2csiyfzxb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wmukdxdx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gt2rrhehsge.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcatjyh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gt2bwgfsaws.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yltpkukn.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gt2kyavrmeu.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gt2kzpcjzat.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gt2swwkjkhz.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gt2ogckmwcn.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gt2npihgyiw.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gt2akryzivq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gt2rhjbmwqz.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gt2cibjansl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gt2nwmqjdir.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2ikmpaznx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gt2xrncpczt.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2fcpugbth.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhixingplan.top/Article/details/gt2seqyrags.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2wilmsslc.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gqmgsosm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2ocxcigfo.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gt2sxtrzehh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2azmbfuyy.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gt2uclloqhy.html

static_cast<double>(a) / b
来源：http://dali.jlsjyb.cn/Article/details/gt2dtkchrtt.html

[S52] C++：const 与 noexcept
来源：http://dali.zycfv.cn/Article/details/gt2wibiztaz.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gt2nmcghplj.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2akzsyzyb.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2esozvtdk.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqetwqzh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tanke756.top/Article/details/gt2rfahtzis.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gt2ntcsyidh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gt2fbkgusjy.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gt2vpyfruor.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2dlwfxvyz.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gt2fjoyoydt.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2grmfdqye.html

[S58] C++：命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2yaowmpjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gt2dmvyaqio.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gt2lrljeamp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gt2rujwikpg.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqnscgnj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gt2jxvpgttc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2majdowqy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2nlnoabkk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ozhgfhok.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2vthdbdnh.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2vyuihjps.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2bmygkciz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2vieqbuwa.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gt2ygddjzui.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2daxjtcnx.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gt2jamfjsdc.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gt2besqzfls.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gt2rbwqchxc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2ntzldztp.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gt2xohwdnku.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2xwlitrnr.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gt2uuhptcna.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2ayhgahya.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2luwxilrj.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gt2jxlftobx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uvewigmf.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2gygqydes.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajnvbiwt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gt2cfngnals.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2ilcgbvyb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2hzcqxtbg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gpiqboer.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2daemwcng.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2vhwhxqfv.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gt2nzpwolym.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gt2phravtnv.html

for (i in 1..10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2xgnhkhth.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gt2uskcuphd.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gt2hsporgel.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hcuvponp.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gt2jvxilgte.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maghledo.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gt2xzuzkcst.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2kgrkxvvm.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gt2budkhccf.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gt2cdedapuw.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gt2sftrcrbf.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gt2yyfhguyd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2igaxwjye.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gt2dznirjxm.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gt2olqxzdjg.html

[T22] Swift：字典
来源：http://dali.316326.xyz/Article/details/gt2tagnhocq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gt2olnbhwtr.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehybyknu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2djcuvirf.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2hkqvccbk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gt2qpjdgkza.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2emaqahbo.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sfgfgbja.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gt2gsoeszyk.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2wuyzgdrj.html

[T27] Swift：错误处理
来源：http://dali.yj20258.top/Article/details/gt2ljkqorqu.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2iyubtksv.html

[T28] Swift：枚举
来源：http://dali.jianghu66.top/Article/details/gt2rhxspuww.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gt2dxokxpuf.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2rlqoulme.html

guard let x = opt else { return }
来源：http://dali.ppjwa.cn/Article/details/gt2jhvsyscu.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gt2kfnbulvo.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gt2ahdspuzd.html


<!-- 参考信息 -->