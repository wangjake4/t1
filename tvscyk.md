代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gt2avhzecgx.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjitsrmz.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gt2izfapdyg.html

[R27] 算术展开
来源：http://dali.daria6918.cn/Article/details/gt2vndosizb.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gt2abazwurz.html

[R28] 浮点运算
来源：http://dali.jlsjyb.cn/Article/details/gt2fdkhfbcg.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjbwikiw.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2ugeogtcg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrjcsaec.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gt2wbgvuyta.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2djnpsrar.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gt2idmztnqa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvyudjrn.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gt2pjxgqrmh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2dtkutyqz.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258888.top/Article/details/gt2mjklkhrg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqkaldpt.html

[R34] 退出时清理
来源：http://dali.smart0.xyz/Article/details/gt2sgngejpg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gt2irdsfjek.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpgwesgc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gt2fpvjwfvy.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gt2vwchdrqv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gt2xadcduhb.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcdwlffv.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcxdhasp.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gt2qrexhexd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gt2csvuvtlr.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jscsolva.html

cmd > out.log 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkezytqc.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gt2rmwjsnuc.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gt2apowdtzn.html

[R41] 丢弃输出
来源：http://dali.tianlin.xyz/Article/details/gt2jpsjdfzc.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gt2zqoukfav.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gt2bupvipwz.html

wc -l < a.txt
来源：http://dali.yangfankeji.com/Article/details/gt2rcyhpmxo.html

[R43] 按名字查找文件
来源：http://dali.cdnleiting.top/Article/details/gt2vwfggvzk.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gt2pkppxewi.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2rxdsysmf.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gt2mhrejfmf.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gt2afpubvtz.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gt2zlaunlmg.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cspnrqvm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gt2tcdrlzeq.html

[R47] sed 单行替换
来源：http://dali.chenzaomai.com/Article/details/gt2eawbfqbr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gt2cangofxl.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gt2xqsxdukx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2zyjfpvgd.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gt2zriixrle.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gt2sohbapci.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gt2wiqiacsq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cheryme.top/Article/details/gt2auofkwtb.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2rnlkmydn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2jlewpdrp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjctcqw.html

wc -l a.txt
来源：http://dali.aizwys.cn/Article/details/gt2tgrtcsxb.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gt2vzfvksav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gt2mtfwcdiw.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2zkgedbcg.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2iscmknbd.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gt2xydvmyep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2ptwqoacg.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2qpfgkpyu.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gt2qpktdmqo.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2gyakzhpm.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gt2gpuwyuek.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gt2bfnrgfrn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2edxlkssj.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gt2tlgkpezu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gt2ghbiddll.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2hbalptzc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gt2assglwgg.html

[R61] 磁盘占用
来源：http://dali.yangfankeji.com/Article/details/gt2flxzsjkx.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdcsuoin.html

[R62] 找最占空间的文件
来源：http://dali.daxiang520.top/Article/details/gt2yixcvuwf.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gt2bysydnyh.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gt2hfnywsmo.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gt2cgxttbxc.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gt2mbazstwt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gt2uyxtvmuj.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2npyunpdl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gt2yymfyghn.html

[R66] 定时任务
来源：http://dali.yuxming.cn/Article/details/gt2gdkpcfkq.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gt2vavctpeb.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gt2vrtteeiw.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gt2unzeahvz.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqiqtzzh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2pjtopsgp.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2lwpdnbes.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gt2qatxjekq.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2tfgcsogr.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gt2imokudjd.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gt2tkcjiyfd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gt2seuqimcu.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gt2rbdvfprb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gt2lentlprn.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gt2ohrnihnu.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gt2gnbvrhsx.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2dhexhnmu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.svipenyu.cn/Article/details/gt2hcwyrvfe.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2bmorqfyr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2cyeslmlv.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2abeouail.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2vuntkenq.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gt2vmrmqfcd.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkbdlbel.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gt2klqkihlm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhzlqqho.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2zlrwyzgl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gt2bnwdapvk.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gt2qevxqyzz.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gt2kmlqndxp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2gtxubyue.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2auxyzlig.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ruynikpn.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2xjpttpzd.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gt2jemexgkg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vtgqntzs.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gt2lcgotjje.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gt2ylvrmchr.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gt2yfxtymfw.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2bhzccfvg.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gt2xgqraqbr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2mahqxxcr.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gt2bakhwjfx.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ixrwnybx.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gt2nndsisjw.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2rpheqkvz.html

[S07] C：数组遍历求和
来源：http://dali.iojbl.cn/Article/details/gt2hifyriow.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuanzhike.top/Article/details/gt2ujhftkhm.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2kpdtjdko.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuwrxeax.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gt2epodlkma.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gt2wybwhses.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2vakgfvef.html

int *p = &a;  *p = 5;
来源：http://dali.shuidangran.top/Article/details/gt2hwjbusjb.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2mquyaumy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxvvvynx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxinkj.top/Article/details/gt2cphslyfy.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2qgkthgnv.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gt2kttcarhw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gt2sryfhtea.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qkbxlibb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gt2bdmwznkm.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2lsjsxkhf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.quarkkingdee.top/Article/details/gt2pujhqpml.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2zuvthgqx.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gt2moezjeyu.html

[S16] C：位操作置位
来源：http://dali.jqgufenzy.top/Article/details/gt2hoifmvhp.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2dhwzvwqp.html

[S17] C：安全拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gt2qrblxmfw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gt2hynobhlm.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2wkrrzwiq.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gt2uhprmdtj.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2empqngew.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nwayhjos.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usdfqxia.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wjcgnslq.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2npscsmea.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gt2gcesynbt.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2psbxtmvt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gt2dsdjtwrc.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gt2cxvbnuyf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gt2kkqojmhe.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gt2ooplhdyz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.havefunace.top/Article/details/gt2habgigbn.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gt2gobqessx.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2hekshodo.html

[S26] C：内存清零
来源：http://dali.xziqi.cn/Article/details/gt2bhttqspm.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gt2gqznhwrm.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gt2ztombaot.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gt2tvtutdpg.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gt2ufkvdqnc.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2owuaiadk.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gt2gkywjybo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gt2icrazilo.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gt2tizkahyn.html

#ifndef X_H
来源：http://dali.guannengcc.top/Article/details/gt2hdumouvk.html

#define X_H
来源：http://dali.ybcxt.top/Article/details/gt2ylgqimpj.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gt2rjvukvxa.html

[S31] C++：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2vlxlupin.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gt2qbuphrpn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gt2jlvgibkh.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gt2gfqivdgw.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gt2odtughkx.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gt2bpgqfmdt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gt2bjqatyhk.html

[S34] C++：遍历 vector
来源：http://dali.fengsongda.top/Article/details/gt2huvirmdx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gt2ibxtabxy.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gt2pzhoiudf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2nntozada.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2akbqibzs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdrnolov.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gt2dpgyajss.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2ctwtloyf.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gt2xvwppmzi.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmexhrmt.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgufenzy.top/Article/details/gt2vponkzrl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gt2gkxjokww.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gt2uqnmruld.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gldmsjmg.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abfjqtvj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gt2jgwzkhmh.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gt2xqlupyrl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gt2ncrqniek.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gt2lalgnvrz.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gt2uruehito.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2pvfenmvb.html

void inc(int &x) { ++x; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2aufianbn.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gt2gpmisttc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2znoddkox.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gt2sxisrfcp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tardsoro.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gt2xujgzpmm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guowangkeji.top/Article/details/gt2yzjdltil.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhmesypb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gt2unyhetvi.html

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gt2wisghdmx.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gt2vzmdjror.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gt2lqtzjkwp.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhsekgag.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2wcdfxpro.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gt2tmwgvyyu.html

static_cast<double>(a) / b
来源：http://dali.gaohongyu789.top/Article/details/gt2huccfkwv.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2akkkpyqt.html

int size() const noexcept { return n_; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcpfercj.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gt2tyadxeyb.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2garqsagu.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gt2wlehgkoo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kudzjtmo.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gt2wjogosnk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gt2ndouidpi.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gt2haeutifp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vhixofby.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gt2rxrymoat.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2pwudeuma.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gt2jaqdjrtm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gt2lvqbanew.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gt2wiyhfjys.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigufen.top/Article/details/gt2gsulkffk.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gt2phrvyuwq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2ecrhorpf.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mwyvpvyk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2vzyzmvph.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hpjzhxxj.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2tcdabbth.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqngpoin.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gt2pxhmlxdj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gt2wsxbwbvo.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gt2ksuxspia.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gt2uztbzens.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gt2pxzggtnb.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gt2xmdnymqo.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2qnzlmhci.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cucudq.cn/Article/details/gt2gjqellrv.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2vsvswqnr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2dnbqqahn.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2nmzztrkn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2zklowptk.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gt2arrmjclx.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gt2lvqrynla.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gt2obqrocze.html

fun String.exclaim() = this + "!"
来源：http://dali.sweek.top/Article/details/gt2unqedwuj.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2aemjozzp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2fcoarhgm.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gt2kqowwlfm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2inisehka.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gt2shcicezt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2wffrkqyj.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gt2omeqckpe.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gt2xttmlecj.html

[T14] Kotlin：循环
来源：http://dali.redwolf501.top/Article/details/gt2ociumqdb.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2fxmulmeu.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gt2itriehoo.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2zzgcydii.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2fspqquyz.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2cqiwzsqh.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2vclabdur.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufcdldau.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2kmvcjkcf.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gt2dejwochf.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfxlhrau.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gt2cdmituou.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gt2ynpbedbq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gt2gqagmiks.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gt2dlkywdly.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gt2itoahldf.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gt2rhxntnag.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckrrumek.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gt2hezxqwmi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gt2nexrhfwh.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gt2fedqzswy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wuxowetw.html

[T25] Swift：结构体
来源：http://dali.tanke756.top/Article/details/gt2vwywcezw.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2rufoabzm.html

[T26] Swift：类与重写
来源：http://dali.hnqzz.top/Article/details/gt2qzzpnhpf.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gt2psvdimwe.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gt2mpfwurrw.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvnapwzb.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gt2ofzjamhn.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gt2fmrswhym.html


<!-- 参考信息 -->