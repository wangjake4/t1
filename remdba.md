代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2bjnqtgro.html

[R30] 函数返回状态码
来源：http://dali.hnxiangtu.top/Article/details/gt2zgjfmpjm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dxjtcqbq.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2jhyxnkhr.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gt2qsjinqch.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gt2vussgbyh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gt2owlvgzzu.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gt2twukbiln.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gt2smsocwjp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tffcizqp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2ihpmdzfr.html

[R35] 后台执行并等待
来源：http://dali.cqqwz.cn/Article/details/gt2rvtquhbh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gaohongyu789.top/Article/details/gt2unombwxh.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2pcitrihv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqxlsfwu.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gt2eqbklyxh.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gt2wytbtldg.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2olvuqokz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhengqikj.top/Article/details/gt2wiboxoby.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gt2sqhnvbwm.html

cmd > out.log 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgoxfbis.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gt2fpdthhcm.html

echo "log" >> out.log
来源：http://dali.sufxvd.cn/Article/details/gt2zavjzbip.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2lccaexqm.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2famackpd.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2rqhoafss.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2gqjjhqey.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2pmftzwim.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2axsucnmh.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gt2jcnxxgve.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2hjrxuxqa.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gt2utckkbbl.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gt2huryemaw.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gt2ujqdgfho.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gt2wxbnmpjb.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2gezzwsql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrlybxre.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gt2qllnfuhl.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2krvxanzu.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gt2oefjcneo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gt2uaevjhub.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gt2hynkiilt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dianchejie.cn/Article/details/gt2odtfhhew.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gt2hzbzyjwr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gt2sovnowjl.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gt2laaartwx.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gt2oyvcwzyx.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gt2ogmeuugj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhsqrhta.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gt2bprojqjm.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gt2otklxzbt.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gt2trsxlded.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dianchejie.cn/Article/details/gt2vayuonvn.html

[R56] 远程拷贝
来源：http://dali.ivvv.top/Article/details/gt2wyluywjg.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gt2mzxjwrbx.html

[R57] 远程执行命令
来源：http://dali.sxryk.cn/Article/details/gt2sdavsrns.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gt2oihpozfo.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2fmgknenk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gt2xiqdtizq.html

[R59] 发 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2czyxozmm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gt2qsyhgpak.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gt2opquxrmt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gt2igcizmeo.html

[R61] 磁盘占用
来源：http://dali.cashguo.top/Article/details/gt2fzxqdyeq.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gt2jcajxsee.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gt2ijjmggda.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gt2uvknwlfa.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2bkzstptf.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gt2nzvwycxe.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gt2zgokmkue.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gt2bbhlbtht.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gt2powpjovl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gt2gozvxaze.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gt2lxwyktvp.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvcderon.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gt2hlcqylhp.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wytmjvro.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gt2hmidcfsn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjqhrfuy.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gt2arikhkgp.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gt2irvmhjrr.html

[R70] 时间戳与互转
来源：http://dali.fzhhl.top/Article/details/gt2kdopwvyf.html

date +%s;  date -d @1700000000
来源：http://dali.sweek.top/Article/details/gt2xrlkiawl.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hffrxqkk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxtkfkkz.html

[R72] 等待端口就绪
来源：http://dali.tian-w.cn/Article/details/gt2lfbgfaso.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2qofvngtp.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gt2hedmdgzc.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2zbgpytvx.html

[R74] 批量重命名
来源：http://dali.cdnleiting.top/Article/details/gt2ahrhuypd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilqjzdyt.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gt2ekbwfuxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2jmcumizc.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gt2cnvbncpc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cucudq.cn/Article/details/gt2wrmgwson.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gt2vxgtnlum.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2piycimbs.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2scilikcd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gt2yjpxewjp.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrvkiayj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gt2wthlykbi.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2bttrbkrk.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gt2nxzlinfw.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2hizcavqi.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2yhlqyyza.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vllrjnil.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2cezsyaey.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gt2szoggosb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2uxixtmow.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqiirxhp.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2vmuguteu.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gt2jzewlwxa.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gt2jznumoyi.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gt2eimkzjvq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2sbcpweoe.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2ipejzcxk.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gt2nrcqghip.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2kcfltsgq.html

strcmp(a, b) == 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hqptsmqe.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2sggbzgcr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2ckbuquwt.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gt2fesomnxg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gt2civjyirh.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gt2evpfhcyj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gt2alyldakt.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2oumajvew.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gt2svnvwrxc.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnmicsiz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2vkvioxxi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gt2vdfrlctt.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gt2gqvelztq.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gt2gzowohfh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2omtowonz.html

[S13] C：宏定义
来源：http://dali.jyoumei.cn/Article/details/gt2saunvlfz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gt2vuymugbq.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnapzxmg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gt2azbqlqnj.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gt2kmkfjtcu.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gt2mldqzxdz.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2asozrztb.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2vyhkjyzg.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2ldsltlkt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2fwevvbdd.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gt2brtwrkkh.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gt2doeboqdm.html

[S19] C：快速排序
来源：http://dali.yvedp.cn/Article/details/gt2ytkazcnv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enlvczhp.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2cnadgcyo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gt2uvxposul.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gt2fhgifoxm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgzqgipd.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gt2dwjrtzuy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gt2rkfiymal.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gt2jjxgbwgc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2qqvblznv.html

[S24] C：获取本地时间
来源：http://dali.nanxuanxn.top/Article/details/gt2nmrbavto.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gt2hcdwijkh.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2zdnpwcyv.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gt2vdljilse.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gt2wchavolf.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gt2mcbgzncg.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gt2sbsrztro.html

const double PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gt2bdsboydx.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kfwramvg.html

static int counter = 0;
来源：http://dali.cashguo.top/Article/details/gt2siwtkhqz.html

[S29] C：变参函数
来源：http://dali.sxryk.cn/Article/details/gt2jdcksmst.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.vqdsnc.cn/Article/details/gt2lwqpmohq.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gt2yboglbpe.html

#ifndef X_H
来源：http://dali.andypj.xyz/Article/details/gt2teowbqfu.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gt2wjybadju.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gt2snymjwaf.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2offalqbu.html

#include <iostream>
来源：http://dali.birdmap.top/Article/details/gt2hvnultmg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gt2eprrebry.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhdintin.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ylpuajar.html

[S33] C++：vector 增删
来源：http://dali.sysykeji.top/Article/details/gt2sfcjjxzj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gt2nzdpjzlo.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gt2refptevy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ombwrmse.html

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gt2mryrjlme.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2cpvkoria.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gt2hdunrzjd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2yygnhieo.html

[S37] C++：set
来源：http://dali.zdqjudy.top/Article/details/gt2scvxdgtb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gt2xebtwhji.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gt2oamgnbai.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2drzrjfek.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2ogdspscp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2rhgxhmiu.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvgszatt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gt2urhjjvfi.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gt2catrkdsi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gt2xinspadl.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gt2merwigrw.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gt2mxnqyhsf.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gt2megeuali.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2pwjaaznt.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2tdrcrlpr.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2kjxrmyws.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gt2wyvmbnre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2wpigmztl.html

[S46] C++：函数模板
来源：http://dali.gogol.net.cn/Article/details/gt2wlaqajdw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gt2xfdjlzsc.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2mblpvswm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuanzhike.top/Article/details/gt2ydqozfhf.html

[S48] C++：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2nungarhp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fengsongda.top/Article/details/gt2tsirbwnu.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2csggjjdx.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2wgtnxnwa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mutgxwsg.html

[S50] C++：格式化数字
来源：http://dali.ydzc1.top/Article/details/gt2twlrszbu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2xlggmujs.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gt2twgwvlrl.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gt2bhoxogoi.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gt2mjvbmapk.html

int size() const noexcept { return n_; }
来源：http://dali.daxiang520.top/Article/details/gt2gkkpggen.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gt2qkteesxf.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2xnxnxvqr.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2itoeqiqt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gt2vaiatxxi.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gt2afbntkrj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akvbvknl.html

[S56] C++：optional
来源：http://dali.gotoacloud.top/Article/details/gt2qnjgigym.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gt2ruenkdpo.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gt2ngtkteso.html

constexpr int N = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2qcaylswv.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2idyyxagq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gt2obycbnxv.html

[S59] C++：静态断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqdwqklf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqrkcolw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2pecrqzdg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gt2dyenqlbh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2zlwrcdzk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2znlzfesr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2kshvyaky.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2xupdzfeo.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkqkiykm.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gt2mdbyqhch.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2pvkhcdjy.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oufakyvy.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qohxklvc.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2uadlvrui.html

val n: String? = null;  n?.length
来源：http://dali.nanxuanxn.top/Article/details/gt2tzgxwqyf.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2njqtviwg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2jvhxvvnk.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2cvaacdcq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2oeecnjpc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2spkkgpgx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2rbpqonnc.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsqarycl.html

data class User(val name: String, val age: Int)
来源：http://dali.hysaishi.cn/Article/details/gt2lhjzztdw.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gt2jovyggcr.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gt2dbqwvvxt.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2gupijleu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aizwys.cn/Article/details/gt2hlddmwol.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gt2xrroevjc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2wucsuqeo.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gt2fandbveb.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2cjkgfdih.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gt2baxvbanz.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gt2tzqzrmwe.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gt2ipxtuyop.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2qwhesecg.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gt2cqumulfx.html

interface Shape { fun area(): Double }
来源：http://dali.haohaochexian.top/Article/details/gt2kzxvtovk.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gt2fumumzhu.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2ijdnoaeb.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gt2cixuczvo.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gt2ikqnwpuu.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2dbqvdzdc.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqznuvpd.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2kqgbtwsx.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gt2vntkqjhw.html

[T20] Swift：数组操作
来源：http://dali.bjfxy.top/Article/details/gt2rppyfhgf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gt2zsfqltyq.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2vriplyrw.html

for x in a { print(x) }
来源：http://dali.sxryk.cn/Article/details/gt2vsggrzmy.html

[T22] Swift：字典
来源：http://dali.gaohongyu789.top/Article/details/gt2hpugoahi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gt2yzooazpb.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gt2peupyouu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2rhqcdeyj.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gt2kfvdpnwd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gt2uymeeigd.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gt2rnhrngky.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gt2vvlwqhxh.html

[T26] Swift：类与重写
来源：http://dali.ehwqpu.com/Article/details/gt2lbrlbzkf.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gt2dpfupjgc.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2kuhtityv.html

do { try f() } catch { print(error) }
来源：http://dali.redwolf501.top/Article/details/gt2nlhniadp.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gt2btxzeyna.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxodysxw.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gt2wwfvhvbs.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gt2nfmkifam.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gt2abwekjdi.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gt2rnkteuse.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2onnrknnh.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2nwvgtsde.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2yjpornfn.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gt2vduqepup.html


<!-- 参考信息 -->