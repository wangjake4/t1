代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgonijhdt.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gttyzcefko.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xuanzx.com/Article/details/gtmwqykrba.html

[R31] 局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gtkqolkmwa.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtkbqzyhhh.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtrgdnaynm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtscofmjyz.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtxlslvnmn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtzrsqrvfu.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtpqdvvwna.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtzysuofro.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gthhxaqfvl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtjtxmaezl.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtpydsdqyc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtjpejfqva.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtdpkdscba.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtqxqlfjsr.html

[R38] 管道串联
来源：http://dali.xylfe.cn/Article/details/gtywbbnyco.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tanke756.top/Article/details/gtfspwqvcv.html

[R39] 重定向标准输出与错误
来源：http://dali.yvedp.cn/Article/details/gtcinunanx.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtrfhfsidt.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtalijfafh.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzzddvpr.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtsiiefzpj.html

cmd >/dev/null 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtuqieizmd.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtcslkbbra.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtfdtznyve.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gttfexuxqa.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtkiybvqnh.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtdjnftutn.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtntuihbpc.html

[R45] 批量删除
来源：http://dali.sufxvd.cn/Article/details/gtdfcnxatp.html

find . -name "*.tmp" -delete
来源：http://dali.hongshengwenyu.top/Article/details/gtqkaesgny.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gtasbbdxgx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gttyoqeany.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gthsanikjz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gtfdgiamjt.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gtochudmbs.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gtqmfyaxkd.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtdwrxfqew.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtuclbxcwt.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtsodtzzkt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtsymbeuuk.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgpbuqom.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtcimivzlr.html

[R52] 统计行数
来源：http://dali.ydzc1.top/Article/details/gtcnuxrkjy.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtikcmydoh.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtkfznyxjy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtcbfpndzp.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtkzazzdvp.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtketfodsc.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtultywqyh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtybygkgsu.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtvndnuxex.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtdhuityhk.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gtmsgnjxwe.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtirxklblz.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtojdtrsur.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtilcpeukh.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtcyxmwxzi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtaefeuasl.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gtbqpanbyj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sysykeji.top/Article/details/gtortlsovk.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtznksqgvu.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtterugtcn.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtyahdwyls.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtvjuavpak.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtpmfnrrum.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gtakaflrwy.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtygyppofn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtaazhbenl.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtduggtzga.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtnnvllbpu.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gttucsnqwg.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gthcrcmheb.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtoxaxrrlw.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtmgljexeu.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtzjetpgpn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtofdpjbcj.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtimhznfxa.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtfktomktm.html

[R70] 时间戳与互转
来源：http://dali.zhoulong.xyz/Article/details/gtdymwjbku.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtikvlyjme.html

[R71] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gtcrahbcbn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gtgezfwomq.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtcoubahkv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtlvpzhiqx.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gtkiynrvlx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtsjrysnvq.html

[R74] 批量重命名
来源：http://dali.yonumen.top/Article/details/gtoyiwgxmk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.c1oappe.top/Article/details/gtvcstarte.html

[R75] 导出环境变量
来源：http://dali.iojbl.cn/Article/details/gthwiiydeu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtxlngdhjl.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtpkxoihnm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtjcalafpv.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtohsvylmo.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtslimjemd.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtmfosvkgo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtywkfipwf.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtbvubjyca.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtbpwaxkcb.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxuanxn.top/Article/details/gtwcugnssd.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gtayimvuqa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjoqwpdgf.html

S. C / C++ 专题
来源：http://dali.kuanghao11.cn/Article/details/gtsampiekc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtufeahqyw.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gthjhlombn.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtrupxnkyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtbisvzifq.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtbwfewhyp.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtbbvscfww.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gtqsqoozfk.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtzoxiaces.html

[S04] C：字符串复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibgekxwp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hysaishi.cn/Article/details/gtqcvcmjoy.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtnqyoohvq.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtogfuttzy.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtnitkcxhq.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtkeatbfms.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gtihjolmok.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gtmcizyfuo.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtnywgjxpj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtwzgffvgx.html

[S09] C：结构体定义与初始化
来源：http://dali.chenjidiqi.icu/Article/details/gtjmvrupen.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtuvjtvtnf.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtoitewpyi.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtqmeaupyd.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtgwapgkzu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtwkmbmxgh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtosvripij.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtejwfabow.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gtfujcidel.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.feifeiyinyue.top/Article/details/gtxmlyzttv.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtliklafcg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcucecado.html

[S14] C：枚举
来源：http://dali.mhx1999.top/Article/details/gtaexaxecu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtwxwdszah.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtruusdqsp.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtnflqjqce.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gthgobonyc.html

x |= (1 << 3);
来源：http://dali.sweek.top/Article/details/gtdbtfntsc.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtamtmdbjc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtsqiqtilp.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtrwsoyrle.html

int main(int argc, char **argv)
来源：http://dali.yj20258888.top/Article/details/gthadvushh.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtlumdlgcx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtrqqqwzyu.html

[S20] C：二分查找
来源：http://dali.snrcjt.cn/Article/details/gtmaxalgna.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtlgfybfqz.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtlwjngqrz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtrmcnimaa.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtdjufykji.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtlwxwsgac.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtuiurlrfx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtrtrtlwez.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtiogzqzeo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtplgvbdjp.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtpomcdydq.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gtbxkzruja.html

[S26] C：内存清零
来源：http://dali.sysykeji.top/Article/details/gtmzsayqbv.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtiyibmckl.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtuwtdsocl.html

const double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtwrprllpy.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtqflfmbtl.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdjiyvql.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gththexfow.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtswzzbook.html

[S30] C：头文件保护
来源：http://dali.cdnleiting.top/Article/details/gtrmwlvwww.html

#ifndef X_H
来源：http://dali.sweek.top/Article/details/gtnjasamhd.html

#define X_H
来源：http://dali.shuidangran.top/Article/details/gthuzdvqgo.html

#endif
来源：http://dali.tanke756.top/Article/details/gtnckzkado.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtzuxeaphr.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtilzmatpv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtsbvufioe.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnrucfvn.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtjhiiaphw.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtgtocbfky.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtsobhqfay.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtaucixcpz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.9152youxi.cn/Article/details/gthtrzgstu.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtofwtudls.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtvsbbjkkf.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtmmszxlzz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtjxqhjzux.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadipgwni.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtpxywpfqa.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gthgrbbpyw.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtcljmcgvy.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtfbqviiem.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtqgdjlvhy.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gttlnhftbf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtvbgzuxfw.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtwsaclexh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gtwhfyzmqh.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtiisnkhdd.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtathxnqmo.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtyjjkrrxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gthdwxfazn.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtysdmngin.html

void inc(int &x) { ++x; }
来源：http://dali.wangdashe.top/Article/details/gtvjjwqsbb.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtzntorfjs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtytbwegop.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtcaawhowd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtaywfyylo.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtvlkhuxvq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtjuuzjofw.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gttdqomokc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtgreyjfjx.html

while (std::getline(in, line)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtnxzwlkmg.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtkfpqbcdn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtuxtweasu.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gttpnobhfa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtuyrompoz.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtlvzeanmz.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtgaqiamnx.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtvxkwbrsl.html

int size() const noexcept { return n_; }
来源：http://dali.shuidangran.top/Article/details/gttyiuwpnr.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gthzwscbis.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnsmgqeo.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtajpptvwd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtktgaohzx.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbnmectz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtbozgwyiu.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtyfondcph.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gtfjbwtxcv.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtkkjriqbu.html

constexpr int N = 10;
来源：http://dali.tanke756.top/Article/details/gtbvlvwlon.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtlwiawxye.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtkvugznnb.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtlfwyzzod.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtsgjrwnal.html

[S60] C++：遍历并删除元素
来源：http://dali.redwolf501.top/Article/details/gtgnrtdetd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyawpaqaf.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtkmugzwlg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gtelrivwht.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtslvloqdu.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gthlqdxste.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtxhbgbkfc.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtorqeuehs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gttvckjvkt.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqaqfirr.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtpngrwewa.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangtech.top/Article/details/gtvamhcqsb.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjlnyfzc.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtymntijtu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtjupuntew.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gttrtgwveh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtkrwkcafd.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtndgyspuu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gthshwvaoi.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtrfdefaty.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtgycmlksk.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtxqmnxesj.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtmsglocap.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntkngihy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtozohxggu.html

[T11] Kotlin：协程
来源：http://dali.zhongyouzk.top/Article/details/gtzcwrtdde.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtllsnzfqk.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtfhqemwxm.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtpdaegxur.html

[T13] Kotlin：只读 Map
来源：http://dali.guannengcc.top/Article/details/gtscawouil.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtcjhujmpc.html

[T14] Kotlin：循环
来源：http://dali.xuetiantiany.cn/Article/details/gttrxryins.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtgrmprulk.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtbernrdui.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gtuxsegmjz.html

[T16] Swift：Hello World
来源：http://dali.yueranfly.top/Article/details/gtgwuqtgqh.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtxwavhzqc.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gtjxbmjvmj.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtryxqztmr.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtfylhqqvz.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtmhougybp.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgxrzntg.html

if let n = opt { print(n) }
来源：http://dali.nanxinkj.top/Article/details/gtsjzdcohl.html

[T20] Swift：数组操作
来源：http://dali.chenlongwang.top/Article/details/gtyewpckhd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtlcayrpqk.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtrnjnfrpz.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtvevxhgbl.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gthdddasgx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtiuauxozr.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtkuqjplky.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gteocjezgc.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbftprkr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.havefunace.top/Article/details/gthmeleqxf.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gttjmihvej.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtebuzpguf.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtdhqqjxlm.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gtqmcxejkn.html

[T27] Swift：错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtiourxrkb.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gtbowoyftj.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtydwluzru.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gtrntvvvva.html

[T29] Swift：guard 提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtmdlxhjzy.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtkiwahyji.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtfrnaphjr.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtflhxyuuv.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtpqktobhu.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtwbukbrjh.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtswlinfaa.html

local a = 1
来源：http://dali.ehwqpu.com/Article/details/gtbvpxnivc.html


<!-- 参考信息 -->