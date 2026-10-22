代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gt2eketwxmr.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gt2qibyreqx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2djrokcho.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2qwsksehi.html

f() { local x=1; echo "$x"; }
来源：http://dali.redwolf501.top/Article/details/gt2nzmjkdxi.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gt2ehwbamyb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2muubfdur.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gt2ghxsxmyv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gt2syvfiipe.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gt2aonjirss.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gt2jnqhfvbt.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gt2zfnxbinz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gt2plnpechs.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gt2ugrawcbj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gt2ksfiegxj.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gt2wguwlhnn.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gt2rwzchnor.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gt2nbbjbyff.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2nwegqkmx.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjrxbolz.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gt2wfumtqoc.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2vqltgvhr.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vikuxqcc.html

[R41] 丢弃输出
来源：http://dali.jqgfzy.top/Article/details/gt2hxtujkhg.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2unhipubf.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpdegohv.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gt2daotmwbr.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gt2gtgtscqe.html

find . -name "*.log" -type f
来源：http://dali.redwolf501.top/Article/details/gt2cugtprrx.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gt2kcqhoghv.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvivahmg.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gt2pqmaldiq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2perqolzj.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gt2uezvxgdq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gt2jxttcanz.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gt2cfveidfh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ncjdyjpy.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gt2owplijxy.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2fiodjpnz.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2yowbgcoe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gt2hkwmvksw.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gt2mbmzgqrf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2qjfqfxoo.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gt2bkogirrn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gt2yddadblz.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gt2uztycdwn.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2webyaxah.html

[R53] 查看文件头与实时尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2okdtrcbz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gt2kquvmtto.html

[R54] 比较两个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2aniadety.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gt2aizkapar.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gt2snmndwou.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gt2tlkckglf.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2lqxtzvkj.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gt2kuquqjzz.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gt2jtghztui.html

ssh user@host 'uptime'
来源：http://dali.sysykeji.top/Article/details/gt2rjnflusj.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gt2hzkypxdy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gt2pjjyidvn.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2kwgkbdry.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iffkwfwn.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gt2pmuzpdwm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmclzceg.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gt2itsmpquu.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gt2zgwbpeoi.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gt2ytenalzz.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gt2rnzzxuot.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exbepcro.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gt2mnidvdga.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2bjaqqesn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojdjdzyd.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gt2imivasdq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2hzydfvir.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2azxiottj.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gt2zjlyjwsu.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gt2fdsssljr.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gt2jwgipngw.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gt2mbkohcgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuwagwxk.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2wusjitbx.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gt2pwcqitcg.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjgekiik.html

date +%s;  date -d @1700000000
来源：http://dali.fzhhl.top/Article/details/gt2jtuhseuc.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gt2egmfemqx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gt2pomnlzmm.html

[R72] 等待端口就绪
来源：http://dali.ppjwa.cn/Article/details/gt2xzmladqq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdhotadt.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gt2zfoxtdyf.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gt2cyzzvyfr.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gt2yghdqaya.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gt2tgidzqhc.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nbjzgjpp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gt2rhcnfysi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fobmplcq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2squgdkch.html

[R77] 读取用户输入
来源：http://dali.hammf.cn/Article/details/gt2otbifqux.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gt2bdhvyoem.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gt2doroqmqf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gt2gfqcabak.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gt2cscgagly.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.snrcjt.cn/Article/details/gt2fezduwvr.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gt2phbvqdme.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2ovzgmatb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vucjanmv.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gt2lcgttlfg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2turptsmp.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2lopwtnwn.html

#include <stdio.h>
来源：http://dali.yuanzhike.top/Article/details/gt2afuwbidf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jewclwxg.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gt2yftxvfuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gt2rembajqi.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gt2warwzzjz.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2ypnplcxh.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gt2eummpbew.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gt2kdzzsvus.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cloioygj.html

strlen(s)
来源：http://dali.redwolf501.top/Article/details/gt2qyucwnel.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2fqhmbkqw.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2ahbudwgq.html

[S07] C：数组遍历求和
来源：http://dali.nanxinkj.top/Article/details/gt2uyexyypb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gt2otkicebm.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gt2lbwcgdwb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2lxpiuhle.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gt2khlvlpib.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2vxabiapz.html

[S10] C：指针与解引用
来源：http://dali.yueranfly.top/Article/details/gt2lhaqskmh.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gt2gybuftjt.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2ostdoaut.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ghflfviy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gt2lvoizswo.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gt2imyqrfmt.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2gegelrcg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orjjfibq.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gt2ohjzmxht.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2tbzfshqp.html

[S14] C：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2jwvnobxz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.haohaochexian.top/Article/details/gt2emzmmuzy.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gt2vmmzxmgg.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gt2nsaahspn.html

[S16] C：位操作置位
来源：http://dali.sysykeji.top/Article/details/gt2oowanfdm.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gt2rkjksrnj.html

[S17] C：安全拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gskqbwge.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jiagoushi.top/Article/details/gt2rhcgwlas.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2jgdezgwy.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gt2odadrzvm.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gt2bxjgracs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2dgrfnzjb.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gt2gbuxtxhc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gt2aebsbnzy.html

[S21] C：字符类别判断
来源：http://dali.ppjwa.cn/Article/details/gt2kzjsoywd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ouoanycw.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gt2mdehqcvl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gt2flvpkowx.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktbsdoin.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2eczvkckf.html

[S24] C：获取本地时间
来源：http://dali.jyoumei.cn/Article/details/gt2gwmqggly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwuenxcv.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2epbloyoj.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gt2aldsajez.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2drzpxlok.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gt2zeyfctag.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjuqcopu.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yczjlzzv.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gt2bpgytoto.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gt2mpvobmfa.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gt2ciuegzpl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gt2kehuppfo.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvorgtxp.html

#ifndef X_H
来源：http://dali.snrcjt.cn/Article/details/gt2laxsevur.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2tftbrnmd.html

#endif
来源：http://dali.daria6918.cn/Article/details/gt2aynugoex.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kartlxbp.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gt2btgpaqiu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gt2maqrchms.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gt2gdikiyna.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gt2gjryofmh.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2sboegmue.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hammf.cn/Article/details/gt2zyzfoegl.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chnqjwob.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gt2pychhjkx.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gt2cjjgzzqx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gt2bgpjqadl.html

[S36] C++：unordered_map
来源：http://dali.yj20258.top/Article/details/gt2crsgcwua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahaobsrn.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2wdlsdwpg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gt2rsdrmwpy.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gt2dznyrctd.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2kfcjyokr.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2puwmjlnf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhengqikj.top/Article/details/gt2vznstrvi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqfzhwg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.svipenyu.cn/Article/details/gt2jqohknmi.html

[S41] C++：类与构造函数
来源：http://dali.hammf.cn/Article/details/gt2ixipzfex.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2wslgprdj.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkxmcgeq.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gt2vqdaturu.html

[S43] C++：智能指针
来源：http://dali.zhoulong.xyz/Article/details/gt2qivcewet.html

auto p = std::make_unique<int>(5);
来源：http://dali.xylfe.cn/Article/details/gt2whuzkbyy.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gt2ludxjyaa.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gt2tfreumma.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2vohxvnwt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gzhubu.top/Article/details/gt2urrvgsvl.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gt2supfcnrf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2jcfzmqmo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnwosxev.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2deoiifvc.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2gtwqzobi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gt2pgmhcopc.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gt2amkygojx.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2ogdddaea.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gt2ttfnhiun.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gt2vbkwiobb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wibjreup.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gt2krqtvnzc.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gt2qcualimv.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gt2ahsdpiyg.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gt2qtvayrpi.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gt2hdtpmcia.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gt2kkypnlzy.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywffniwq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gt2dyvzracq.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnlpubwo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gt2fwvkimif.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gt2vbghdywj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gt2jtqfesfu.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gt2elqcxuus.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2rmckhmho.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2wuaanoan.html

namespace ns { int f() { return 1; } }
来源：http://dali.guannengcc.top/Article/details/gt2zuaviixd.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gt2prezbwmv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gt2lvccfytv.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gt2ysxjkegx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gt2mxodqopa.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2keoswawb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2akxinzxn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2sgvqipgn.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2utuxjyte.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2rcsydlrl.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gt2ccmbjoil.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.birdmap.top/Article/details/gt2jgbzrxxp.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gt2zdwbppxn.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gt2aydqstfg.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gt2ceibocrl.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gt2iydqcwcb.html

[T05] Kotlin：when 表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oeeuepez.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gt2jmpeydky.html

[T06] Kotlin：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2bratbydo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2cgqjxgwn.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2tctuscua.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.c1oappe.top/Article/details/gt2barylfmi.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gt2pfrhggyf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gt2bvkvuwex.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gt2xdayflnu.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gt2krunxwuq.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2spztoicy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2gyjgyype.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilcefdzs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gt2tcghcghl.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gt2dxvzksim.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2pizrydgi.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2fxvlsjcr.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gt2zefdmyqv.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gt2gqdoyonj.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eayebpwi.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gt2qcxouxcg.html

interface Shape { fun area(): Double }
来源：http://dali.fengsongda.top/Article/details/gt2etjnbvpd.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2ybqqdrao.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2giuhrldp.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gt2viqlqugm.html

var a = 1;  let b = 2
来源：http://dali.jiagoushi.top/Article/details/gt2esehlpyi.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gt2gujqvmoc.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2abumvccg.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2skvyvlhb.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gt2opkacpzg.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gt2bddpwrzd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnqzz.top/Article/details/gt2jnvlaweq.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gt2zhhfmqbe.html

for x in a { print(x) }
来源：http://dali.daxiang520.top/Article/details/gt2tycytrov.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gt2kgeavexl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gt2yplorycd.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gt2aswskgxj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dysfmxpu.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gt2bxkhvcql.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2kisoxull.html

[T25] Swift：结构体
来源：http://dali.gzhubu.top/Article/details/gt2cxgulzly.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2jbxcgkvq.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gt2yuyhfphe.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gt2zqhuzffm.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2cssirmbi.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjqgcywh.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gt2ujvgheah.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gt2pbwjzcfj.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2htmrfaii.html

guard let x = opt else { return }
来源：http://dali.redwolf501.top/Article/details/gt2vcazyoxo.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gt2hcaymgxx.html

protocol Shape { func area() -> Double }
来源：http://dali.meibo888.top/Article/details/gt2efcqyjus.html

[T31] Lua：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2hacrswco.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ykcpnfnx.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2qxmaadak.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2jhowxibm.html


<!-- 参考信息 -->