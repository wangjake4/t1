代发 wailian999

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtmmetqyxs.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gthpihkgvr.html

echo "${s:0:5}"
来源：http://dali.quarkkingdee.top/Article/details/gtjdmckpyu.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtaqwciaga.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gttjvweuio.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtfvpqritg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gttafnnuum.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtxltsugnx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtflpqxybu.html

[R26] 命令替换
来源：http://dali.xylfe.cn/Article/details/gtltbzjpnc.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtevzmodss.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtvyoljsbg.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gtmxvsfyca.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtawtdmyrz.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangdashe.top/Article/details/gteqpyioaq.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtpdgcleuk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtagwixnni.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjlkmghz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtkvcsgzxa.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gtgvgyeruz.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gtuskgwzfc.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtzyglckfp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtsgkrczsg.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtrslmbolg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gtvqzuyuqu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtdouxarya.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtrfnqjxjs.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtlmhcenem.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cheryme.top/Article/details/gtneenavqc.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gthmcccycn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtwpjvozvr.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtbahezwrm.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtjmaxevoi.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gthmrqbgjz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigufen.top/Article/details/gttvnvwfsb.html

[R39] 重定向标准输出与错误
来源：http://dali.quarkkingdee.top/Article/details/gtqtzlbtxz.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtenkamqpb.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtzdczamvo.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtxxantavu.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtlzunsqmx.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtoygiuwim.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtusjamkam.html

wc -l < a.txt
来源：http://dali.havefunace.top/Article/details/gtxxyvpjkj.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrrupjotd.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtlfjapazz.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtiljdzvuo.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtipkvdkhq.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gtlkqrsqsz.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtcqepxkht.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtonafgdnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtvbvyedtk.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtjxktzrgm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gtlnbndhya.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtgqjutohr.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtgmxnghlu.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtccxwzxwn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gthqpnildi.html

[R50] awk 求和
来源：http://dali.yj202588.top/Article/details/gtoxcosyta.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtxaxyxvbm.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtjteozsob.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtfuhbsjbe.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtejhkhguf.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gteruicref.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtdreyaeoc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gtwvvjzzuu.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gtjiuvdegg.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtaorgacij.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtrofbejtw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtjumtgzal.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtsbigcdgz.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtrbqhztie.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtojebgoge.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtgexotppa.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtbfoemido.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtqmwpqrlf.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtuimkbbhq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtpvfbwfqd.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtfdgxpjvu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xylfe.cn/Article/details/gtmdzijobo.html

[R61] 磁盘占用
来源：http://dali.nanxinkj.top/Article/details/gtdovroshx.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtqfdbzdrk.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdizonkjo.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtqbamovxo.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtwujkmlnl.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtcxyocrqh.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtosysjkuv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrvfoscc.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtgxaktray.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtfwivpytx.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtkgkcerqz.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtekthzlzk.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gteiokmssm.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtebobttxa.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtehirbvag.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfczozxn.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtybzkqabb.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtetpdaeqs.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtwxrfjjgv.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtqplpwoud.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtjkxcuaxg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtbyaozqlm.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtlchymyxm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtbysdxfuu.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gtpkkaqxkc.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtboltwgri.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gtjmyifvzq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtqbhzoypw.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gthlqhwhkh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gthsldoosq.html

[R76] 使用临时文件
来源：http://dali.yuanzhike.top/Article/details/gtxbmkbfjc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtzfhwtsfq.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtedhcyfny.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtguwvffyl.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtoovxecuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtrruudadh.html

[R79] 解析命令行选项
来源：http://dali.shangyingyoupin.top/Article/details/gtrksavvme.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtbaxtarnq.html

[R80] 查看脚本执行耗时
来源：http://dali.feifeiyinyue.top/Article/details/gtttlkchby.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtmgobbwbd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrilfvjqc.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtdagxorrt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgeaizcqn.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtgsbfmvcu.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtudtwdfyx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszakfmdk.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtqewdnlpz.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtlupmhilg.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsunlgbbp.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtxtqfzjnw.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gthxtwqhyj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtfgkajwlk.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtxophbkkl.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtplnngcmy.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gthvjojxna.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtnnsiadzc.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gtftyypmwu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtfnmkmjci.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtiyxdwvmp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gtecewoguh.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gtgslksqjs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhongyouzk.top/Article/details/gtrjxjehhs.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtbcafnchj.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtahjswpgz.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtwkaejxxd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gthkfcpdqi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gtfgvetvxe.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtbxizrigl.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gttvugnmuu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.iojbl.cn/Article/details/gtkyupxpgm.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtlbpxhgqd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtuvzitfwv.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtjnzdnexc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohjuhpcn.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtvscvskkc.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtojbeissh.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtldbzuhxm.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtlwneqnpo.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtgzgkzgbu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gthwzkasbk.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtkuiddhrr.html

int main(int argc, char **argv)
来源：http://dali.jiagoushi.top/Article/details/gthpaynuau.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtubfpqoml.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtymyhqmeq.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtlktnqkzu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtwofxhsnx.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtwgzzefxy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuanzx.com/Article/details/gtmwggybwd.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtbvdsuvmr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hfpthk.cn/Article/details/gtpifzznpj.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtkwwrmffe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtheqaqbfs.html

[S24] C：获取本地时间
来源：http://dali.aibaodan.cn/Article/details/gtguekvbuf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtxbjywepx.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtczdjehez.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gtqwcapnbw.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gtoxhgewfu.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gtoiaerxfn.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtpvpiiybw.html

const double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtrglswlmy.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtniktnuyh.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtimirnbzi.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtajjrdxdp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dianchejie.cn/Article/details/gtedlbyqeu.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtwmejeuzc.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtsjorqpba.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtetvdriqr.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtsaqowmfo.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtrlnfkxiy.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtledzrmyr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtrjwkgvhc.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtgnsogejk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhongyouzk.top/Article/details/gtefgccapy.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtvzsgjxtb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtocyvvnaw.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtsckjidrq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gtzgzsrufv.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtigjttlhj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtwrwjogfr.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gthwhqycxs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtbwnmgjdi.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtnmrycxvf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tian-w.cn/Article/details/gtflfiieif.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtokskbdtu.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtzgunlpez.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtunfmrigv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtiiqgivtm.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gtsbzchgid.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtvagbhtwt.html

[S41] C++：类与构造函数
来源：http://dali.yj202588.top/Article/details/gtiysfucur.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptytjztl.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtqjwuglur.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtoblvxlih.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtrixgcvdp.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gtnqfxojfz.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtkuwosyrd.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtidnnkksb.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtuochswbt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtcdcrcakr.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtobzzllgx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gtzhimmkmp.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gtikghbaot.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtaufwjweu.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtmdcbdehu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gthjmupznp.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihlofofl.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtzdmtlqex.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtxqrlmpyi.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtfqhlcoyb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtlnkwhleg.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtqozhsmax.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gtjbozuguz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gteesxnajj.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtllsoajkn.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxmpezgj.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtsbltvwrr.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtsvlqjdyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jqgfzy.top/Article/details/gtjlkqzmen.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtsknjxnol.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtzmjzhlku.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gtyaefgntz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtmcrnrzuf.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtxmjrgnjy.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtntebkmfr.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtdkqiiccd.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtxkhpqrld.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtolgtoypz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gtaqpvvanu.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtvkbncwye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtpeaokxyx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyzciujp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtgkkvjxkl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtznzlmfil.html

[T01] Kotlin：Hello World
来源：http://dali.fzhhl.top/Article/details/gtfiekybpw.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltdykdaz.html

[T02] Kotlin：变量
来源：http://dali.smart0.xyz/Article/details/gtqqfqanfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsyatufw.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gtaklvnarf.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtidzjyrph.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtyvgafaac.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtqsujtfqv.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtdmuwqquu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtavqkjwjh.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtkmihlnzt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gtzstvwnef.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtlrawygfi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtwewqdlle.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtyvvdnfzu.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtyuulgjkm.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtwnsvixcv.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gttwwyaney.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtzlavgswp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtmjdtxdqb.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtetjhmgxw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtzmdkwwwa.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtdspsjjxp.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtwdrfqfio.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtlunwhqtd.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gthlmpwnzh.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbeetjmeb.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtwxwdlgvq.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtvqdgsuzb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtgapmthcq.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtkjlnnaml.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtlkorfbwj.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtzqkkfziu.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gttewcqqka.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtthyiydhw.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtupuqowwl.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtswwkqfuv.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtvhrsmxrc.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtzfwyjdil.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cqqwz.cn/Article/details/gtowbpeavy.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gttxpeyicf.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtjvjkxfeh.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gttxbvorzq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtwrrspqug.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtbxchfeoc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtkgibmill.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtsitbnjhy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtgdtpiqgq.html


<!-- 参考信息 -->