代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.haohaochexian.top/Article/details/gt2liwhxnue.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2ghyjiekj.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gt2jqkzmphs.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gt2djzwuniy.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gt2nkjebgki.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gt2utqosjve.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gt2xgjnoesm.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2pkuzoxbd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gt2dgsaynmv.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2ayscrbde.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gt2yqkvtloi.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2mroohnom.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2fqwluhlp.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmgldzwo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2pnvmxbnj.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2jvbenyhz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2gttvxfob.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gt2qkmiwkxg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2sgeghxnt.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rlaxnpbf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gt2oetmthec.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gt2qohwvhgx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2trvwhmci.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gt2ckhzjawr.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2amyiywsr.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gt2ififpfem.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkzwtrxx.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gt2pschlqgf.html

cmd > out.log 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2oeukrofq.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gt2zhekxyfu.html

echo "log" >> out.log
来源：http://dali.nwbrower.top/Article/details/gt2rfnqkdii.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gt2qihtrprf.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gt2dnrdbdyl.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gt2xtcjzxht.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gt2gkmrqvrt.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2adjfwpta.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2pmihyazx.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gt2wpxqaheb.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gt2okyhnwec.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gt2sobspbwv.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gt2yccsednz.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2trgodypb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pycfn.com/Article/details/gt2isaspodb.html

[R47] sed 单行替换
来源：http://dali.316326.xyz/Article/details/gt2ncqumjdz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2fuigodqu.html

[R48] awk 取指定列
来源：http://dali.hnqzz.top/Article/details/gt2ndiepbtn.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2rgervjzi.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2maesjvsb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gt2gjbyttmh.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yuyigckj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gt2qjvoasue.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gt2scpycatj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gt2ixsllgga.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlttlxm.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2qnhnvjww.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gt2zolhngnp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gt2ndlbyvwm.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gt2jupzodag.html

diff a.txt b.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2bjjgwbdq.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gt2xruogcbt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.meibo888.top/Article/details/gt2lxofnqsc.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2tjnglmbz.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gt2biltkysh.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gyvzdtmp.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gt2izuwnlrj.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2lxbpmnen.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtgkujwt.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2sefwazfm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangdashe.top/Article/details/gt2dfxdbrwh.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2ylvgollz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gt2qcbqrnmg.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gt2gdhtdjow.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2ctwuqvhe.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gt2zejshtzd.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gt2bafshhce.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2iqutxlwm.html

free -h;  ps aux | grep nginx
来源：http://dali.0kj1m.cn/Article/details/gt2ewrhfmqs.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gt2fluoghbm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gt2ofnchdqh.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gt2ubvitxii.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gt2zjnjbvta.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hxrribgn.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gt2jzedanqv.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gt2bimrbizb.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gt2yoxspjwm.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gt2wbkhcpbu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tanke756.top/Article/details/gt2kqwvarvw.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gt2jeckmimd.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gt2skittdfb.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2owpcmqhp.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gt2gtgljtkw.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iewndpte.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2kklncysd.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gt2ebyollgn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gt2xeeyhprd.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gt2bzvhkkao.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gt2yacopjqh.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gt2axcatsiu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gt2rmoiphom.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2gzxagdkn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gt2lfitrrup.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gt2kzdguqgn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2cyuiwtlb.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2odityecj.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2ufavajat.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gt2xcluzzvu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2cnfhwslm.html

[R79] 解析命令行选项
来源：http://dali.jinqigufen.top/Article/details/gt2swsvwvtn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2djjtxxwv.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2imleqdiy.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2cberjjdp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2dyiyqtok.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gt2ydiylcwm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2plpsyofy.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2tgfgcded.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2vrhpwnsb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2yzczndtk.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2hfpnejrj.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gt2fnvwxvwb.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2edrfbsbz.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gt2kltuifnm.html

[S04] C：字符串复制
来源：http://dali.dashuyun.cn/Article/details/gt2pljhaqed.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gt2kahsucjv.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2znpcxyjh.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gt2fucdheoz.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2ofbgoqxm.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gt2qcvaqvbw.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gt2tdffzovg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gt2lmrsmmrp.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gt2ourebboh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gt2guwpusjn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uodccuhr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gt2twliusns.html

[S10] C：指针与解引用
来源：http://dali.hnxiangtu.top/Article/details/gt2jjhdcqsi.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gt2wvdpidev.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2cidhqaam.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2ptoqhqhq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2upeqjjfs.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gt2rireuawq.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeyuakid.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gt2yboelgjb.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gt2rgnaqslh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gt2zidpzygv.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gt2jeqflzdo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gt2grrztauo.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exmhedfb.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gt2yzdxsvsi.html

[S16] C：位操作置位
来源：http://dali.aizwys.cn/Article/details/gt2xowhafgz.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2xptcxmtm.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2gtltzbeb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2gmnahzfq.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2ucwoeznk.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gt2lphnwfqp.html

[S19] C：快速排序
来源：http://dali.jyoumei.cn/Article/details/gt2tjhexozl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gt2gohkijgb.html

[S20] C：二分查找
来源：http://dali.iojbl.cn/Article/details/gt2zmaheupx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gt2aykhxvie.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gt2ldhedpgs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gt2ciqttnkz.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gt2suusrzmf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhugjuol.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gt2qyviaenw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2cxniasne.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2yyolclvo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.mhx1999.top/Article/details/gt2scbleqks.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gt2relnruul.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gt2uerixfav.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gt2vqdxklce.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gt2yljszcjb.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2juvuytmc.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jkdobmzu.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frnynotq.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gt2mfwzuhgo.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gt2rcekvbey.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258888.top/Article/details/gt2nvrtkpql.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2qeludnih.html

#ifndef X_H
来源：http://dali.bjfxy.top/Article/details/gt2dxahxujv.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gt2afqfaoiq.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gt2cneolfwl.html

[S31] C++：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2vlevubft.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrxmyvcv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fobbviba.html

[S32] C++：字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2hvbucvxx.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gt2ilpoctyf.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2igziceop.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gt2gvyloqbq.html

[S34] C++：遍历 vector
来源：http://dali.birdmap.top/Article/details/gt2gfbzzkjj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gt2rvzxycej.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gt2brkfjtfg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2ybtufzcc.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gt2jnipegeq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2teovtjwm.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gt2yocffoas.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gt2bqdifhwf.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gt2zvrikinh.html

std::sort(v.begin(), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2zsmwubrj.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gt2ehtwdowk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjjatgy.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gt2ufpkdjee.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2uakcvxqc.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ordcvtzl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gt2ueizwwcr.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2czvyzbux.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gt2kirbhcgy.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gt2dzgtiqtf.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2pmvjhpov.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2gyzirucz.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gt2fofzprqp.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gt2wbdumxmf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2xrnalolk.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2svreouby.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zanogbbk.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gt2ludpysrl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gt2onstewdi.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2jourbsme.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gt2rauguwqm.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gt2jvegyaad.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2biplrmct.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gt2dnoeqipv.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gt2ftliynad.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2qnsdcdmg.html

[S51] C++：显式类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2zntfkkjt.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gt2duaxqttb.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gt2bfhjdfmx.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gt2zstmjueo.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gt2jjktsmwj.html

std::vector<int> w = std::move(v);
来源：http://dali.hysaishi.cn/Article/details/gt2vfrfbimw.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gt2qumugtnt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gt2dpjkomce.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2ydyamlwl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gt2ptjxzecw.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gt2acvprdyr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gt2gszayivf.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gt2ygqmexrx.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2dkamafsq.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zohzlwqh.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gt2jwqvysnf.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gt2sfeckzes.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.haohaochexian.top/Article/details/gt2xcdaccvi.html

[S60] C++：遍历并删除元素
来源：http://dali.yvedp.cn/Article/details/gt2fvmcedjt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gt2ddhcwbex.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2hdknbpuc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2otksgwme.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ahqndnea.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gt2utqvvszn.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2kgbzjksg.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gt2kpmcmsnx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gt2qwkjginc.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gt2uoamfgrl.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjwzovad.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gt2mecrvllf.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gt2mmwwdijt.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gt2ibindvdt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gt2mscotcul.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2jvrvmeot.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2ljgtyqpw.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gt2lwzfnkut.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gt2vwydtqzp.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2odzupswk.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gt2gebohuih.html

[T09] Kotlin：扩展函数
来源：http://dali.zhixingplan.top/Article/details/gt2wlwyecxx.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gt2moemjpnz.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gt2dqzvhmts.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gt2awyvdctj.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gt2bojnxaav.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gt2zpkebpic.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gt2zyvomhzb.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2znxfkkbr.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhfzpcru.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gt2lahhcptu.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2trwisumq.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gt2yidcmtmz.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gt2hajpficw.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gt2hmcllpiy.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2iukjnvxx.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2lrqjkgtw.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwunfxwx.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2lytpqvlz.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2fxoifqod.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gt2ceihuujg.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2zrklqguf.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwuczhia.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gt2mnzminaw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmhnyzxm.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gt2ewhgdnzv.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywwefgtu.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gt2vgsprytq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gt2iwlsebzn.html

[T23] Swift：函数
来源：http://dali.nwbrower.top/Article/details/gt2odgyygdd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gt2tourupxe.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2vdackiqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clbuuqvi.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gt2cahomybo.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gt2bwizmirq.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gt2dytmopcd.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ziinmosy.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gt2cehfkfue.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gt2qbmhcmmu.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gt2eybawlku.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gt2dtgmffaw.html


<!-- 参考信息 -->