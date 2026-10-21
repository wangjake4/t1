代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtwrarlvoe.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtnpvpwkdz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzfpnstj.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gtcghdwvxz.html

echo $((1 + 2 * 3))
来源：http://dali.ppjwa.cn/Article/details/gtewmxkdri.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gtldfwlvwj.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtvfgflhqy.html

[R29] 定义函数
来源：http://dali.smart0.xyz/Article/details/gtykbfslwc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gtcastdwdl.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtomrpmjld.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonknpkyy.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtayclzopg.html

f() { local x=1; echo "$x"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlqjatoaq.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtqfnpdnqs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtveckikgs.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtkwslxnzo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtvvxdqqyz.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gthjgomnkd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtwxrfxqjl.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtxxzbrjka.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtgxfogkab.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtdchwicph.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gtgsmuytzf.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtgvhmubpc.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtaookiflt.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtdfqdezqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtfuzriiyc.html

[R39] 重定向标准输出与错误
来源：http://dali.wangshuangyany.cn/Article/details/gtsoaqazdw.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtmyilwsbk.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtbbogbgmo.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtapnwzjzg.html

[R41] 丢弃输出
来源：http://dali.hongshengwenyu.top/Article/details/gthsqgxfuy.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtjxvaflhm.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqhxjhfe.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtabidectr.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtbbzsatna.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gtugxkmdcd.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtnwgzzwpp.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtxarqyqda.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtcjnmyylx.html

find . -name "*.tmp" -delete
来源：http://dali.aibaodan.cn/Article/details/gtbrgvbbuz.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtlepsnrih.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gtfjmobviw.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtjmccgxhw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtslfrwsqy.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gtbwkerxqo.html

awk '{print $1, $3}' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtdvcfnkwh.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtwfwgvrrn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtfljqezor.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkmqdbdj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gtvichzxcf.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gthxlnyafj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnxiangtu.top/Article/details/gtyrkwqtms.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gthtxxdokw.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtzwzesghs.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gthvmvhbbq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtxpwmwlrh.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gttpmatlpx.html

diff a.txt b.txt
来源：http://dali.ybcxt.top/Article/details/gtflsoeigq.html

[R55] 压缩与解压
来源：http://dali.hfpthk.cn/Article/details/gtcowktqzh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtffcxjezy.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtddqqpbhk.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gtndfgojtc.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtvcsygwpm.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtnrktjttc.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtxoydeere.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tian-w.cn/Article/details/gtaizrddzd.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtprxdrefh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtzlriowrh.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtdnndpxzu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gtkhqaiziy.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtlroaownf.html

df -h;  du -sh *
来源：http://dali.zhongyouzk.top/Article/details/gtyjbeefxt.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtugublbfq.html

du -ah . | sort -rh | head -10
来源：http://dali.ydzc1.top/Article/details/gttxrmmsbx.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtejutbeoq.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtumshtblx.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gttbdsqwpu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nanxuanxn.top/Article/details/gtehpmujmd.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtchsrqcco.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtepsnenys.html

[R66] 定时任务
来源：http://dali.yonumen.top/Article/details/gtwrcehryh.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gtwfbvfoes.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtftcbglez.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtnmuyglzi.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtlnngvrew.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtesvyayzg.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtixzoagld.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtbizzbgwu.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gtqvifcqhp.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtkkmvyals.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtqibhmtrr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.mhx1999.top/Article/details/gtcjsliauc.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtenikvcgf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtjmllggre.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtkujxdwsw.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtiecgomeu.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtpevjrtfx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtarvwpczd.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtxefuahpt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtdwntsswg.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtdioctwbs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gthyalxvsf.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtshxjhurs.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtsdvijrnt.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtzdfmfkqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtcjhoxohd.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtkolivgez.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gthwmfcpwz.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtrdqoysse.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gtiisupwvm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcmsiuwbg.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gtxwtvpnbz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtxhpascek.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtetvuxrsu.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtnvgnfwil.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gtconalkpq.html

[S02] C：变量与格式化输出
来源：http://dali.ivvv.top/Article/details/gtqlelieye.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtmygkmpyy.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtetkrgfko.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtyqjuevxm.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtisizsddo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtvatyguzi.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtksehghor.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtsjpxevjw.html

[S06] C：字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtphlmevfl.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtvqafbkwq.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtvoxshsxf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangtech.top/Article/details/gtidtxlyyc.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtxldfhndg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtqbvbwctc.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gtnoftqpnv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtthezwyde.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gtocnagcox.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtfuubuxsn.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtxbldcbyg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkjabaem.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigfzy.top/Article/details/gtalnrvnqh.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtbsitndcy.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtcwnupvff.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtlvzvaifd.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtlsbtwbzu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yvedp.cn/Article/details/gtytwampqd.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gtzolwicah.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtrcwdynle.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpwihugb.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gtzazqqrly.html

[S16] C：位操作置位
来源：http://dali.svipenyu.cn/Article/details/gtavjwxavp.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtonxpvkck.html

[S17] C：安全拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtdvopkjas.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtfyajrnqy.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtsrdcxtau.html

int main(int argc, char **argv)
来源：http://dali.0kj1m.cn/Article/details/gtxfagqanu.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtjpltmoat.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtjeinonae.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtokdehiam.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtbgqybcrv.html

[S21] C：字符类别判断
来源：http://dali.jianghu66.top/Article/details/gttawbdujh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtkulfeoky.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtsysigcxj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtanattdps.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtrysaobsx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtajfipowj.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtaoeuoyll.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtesvyjqgq.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtkqbqbjjp.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtnwjyandl.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gtrjyenxac.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gttwvfztun.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gtavxhrjae.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtpyxsgcno.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtwfwxktxf.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtplbicybk.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gttzlixkkf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtvqxmcmqw.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gttzwbpbcq.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtpykzcsps.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtjnjcqdvy.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnewbrpz.html

[S31] C++：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufgladqr.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gttlyqfxju.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtwxcacfrs.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvopqfax.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtkefqpqss.html

[S33] C++：vector 增删
来源：http://dali.shzxlz.cn/Article/details/gtdgqleint.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtawobpxjx.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtuxgmbrux.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtonpbjrvo.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtjsanhfjk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gthtaihnbw.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtcbyyekxg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gthqivqinl.html

[S37] C++：set
来源：http://dali.tian-w.cn/Article/details/gtizhrystp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtbvahdgrz.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtbyhfnypx.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtribtfbit.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtjbozaflv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtxmhoejjq.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtoojxjhlo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtwblzvtfk.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtevhuuchw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtdjzxpfys.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gttubruihl.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gteidcefnj.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtdakwuuue.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtcropioaz.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtkqofevnc.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtmurjdcbm.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtterqjbxf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtkfojyrkb.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtvmmliazu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwsqebwwg.html

[S47] C++：结构化绑定遍历
来源：http://dali.mhx1999.top/Article/details/gtdjzrueuk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtqggqzomd.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtdzayagll.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gtjohmejrc.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtrynnxkzj.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtjumuicoz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtvvdqyvux.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtcrmeixiz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtautmvsnk.html

[S51] C++：显式类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjfnjzpn.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtrjbffcxp.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtuwargydj.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtaskcszlg.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtlbngpotl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gthdlrdzat.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtludixlcw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gthlyjfyqh.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gthympjobm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtfrfxivrt.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtarlfkxtn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjaycgcnr.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtihsvljdy.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtzvhgrity.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gtlmulxcko.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwgawrni.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gthmizlwmr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtffnrclfa.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtnnydycez.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtmxggthxj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtvjfrissj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtpparmpem.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtskzheucz.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtyslafytn.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtfcyrlyvx.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gthzksvwdh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtjewvqyxw.html

[T03] Kotlin：字符串模板
来源：http://dali.ydzc1.top/Article/details/gtkgaequzs.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtanrqhokm.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gtgdqrzrys.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtpuhuaycf.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtjqgxmkbk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqscetdk.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtuyjsawqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtkpcbzjgz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtacvygeuh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtcbkuulab.html

[T08] Kotlin：数据类
来源：http://dali.guowangkeji.top/Article/details/gtncnnzyse.html

data class User(val name: String, val age: Int)
来源：http://dali.c1oappe.top/Article/details/gtndnbtvtv.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gttproffmv.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gtnibzeopd.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtzgplxrfd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtihljroga.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtdortzuia.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gtwndwauvc.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtxitellon.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtpebtsyyv.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtgyucnxdp.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtqckyrxdk.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtepatgfbz.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtjdbqtzbv.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gthpwzsodq.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gtogfaafxc.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtaeywcctt.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtwhowcjce.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtcsfctnmf.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtkqeehovv.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtsijixstf.html

"值: \(b)"
来源：http://dali.guowangkeji.top/Article/details/gttcmedpjn.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtcmjpcldt.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtnztoccyn.html

[T20] Swift：数组操作
来源：http://dali.chenjidiqi.icu/Article/details/gtxugvyqio.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtubgiusca.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtsnlifiyw.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtwxvbjztf.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtnyopdmkc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aibaodan.cn/Article/details/gtevtofhtd.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtkdkewxqq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxebtnutf.html

[T24] Swift：闭包
来源：http://dali.zdqjudy.top/Article/details/gtkuqvqewg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtxqjmmrhv.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gtgrvbhauw.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gtczowjovx.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gtardunbmw.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtklqdiosv.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtxcqtcncz.html

do { try f() } catch { print(error) }
来源：http://dali.hfpthk.cn/Article/details/gtqtbxigyp.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtgnllhwkl.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtvucnyjxt.html


<!-- 参考信息 -->