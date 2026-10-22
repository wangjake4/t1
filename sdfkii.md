代发 wailian999

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtfndbsmoc.html

[R22] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtpuuetqwa.html

echo "${s:0:5}"
来源：http://dali.yj20258.top/Article/details/gtpotbnitk.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtmnrtdbai.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtpmxyxatu.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtxpwwgeta.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtfnxwckrl.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gttbmujluc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gtjjusuvgz.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gttbzxfyfr.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtszftiegh.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtdunjlcca.html

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtcvyuwsas.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtxihkcwwz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtzbssknqc.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtuxdampaj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtjsqnkogb.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gtqasahnai.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtgzxffuka.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtwluvyfgl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtkucpatok.html

[R32] 参数个数校验
来源：http://dali.tanke756.top/Article/details/gtdoidwehs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoghjaaf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtpplgprtt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ydzc1.top/Article/details/gtpdcbnufk.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gthbfmldja.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gthburtlek.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtjqhyvxtd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtjlijxjdv.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacnlqhtx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtppfqaqyj.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gtquyhyaqe.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gttmpkpges.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtfnsunpuf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtaphabkyp.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtofsujohm.html

cmd > out.log 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtytkkdztu.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtriqguuxi.html

echo "log" >> out.log
来源：http://dali.yangfankeji.com/Article/details/gtcavllusl.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtbydvsqwv.html

cmd >/dev/null 2>&1
来源：http://dali.yvedp.cn/Article/details/gtgflkbygg.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtkvmzdsay.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtsuyknfio.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtdyjnhsyl.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtzapjento.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtroptfykb.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtqmhpkbjv.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtakjexuve.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtcuudvkep.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gttgumdafw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtpdfukttt.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtaoelesgk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtabvoagvi.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtojwrmshg.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtvxvctzyi.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtwfbsnsnh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gtngkohino.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtldqyhggh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtuqscmsed.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gthwaqkyfu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gtnfnfzjfu.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtprilqoid.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtabynbvcv.html

[R53] 查看文件头与实时尾
来源：http://dali.chenlongwang.top/Article/details/gtmafhhsyd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtvapoehbh.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtgwmuyjzt.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtwgthivuz.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtdktaiaha.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gtqpfujxpi.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtywrjadcr.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtlcaqnifu.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gtgbhrhcbu.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtmyhthfqm.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtutjihydn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtqteamlxr.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtizziqklw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtaxtadiid.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtbhlyeuua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtxsvcgqwo.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gtyniummsj.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gthvwmcddb.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtcbnmmbog.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gthhmgqech.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gtnnkzfxjw.html

free -h;  ps aux | grep nginx
来源：http://dali.vqdsnc.cn/Article/details/gtwjjvwnxh.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gthjbopqmn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtdicugedy.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtvbrfpdls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtsfmmycbi.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtrpmnmhsk.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtpzennova.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtkkswmqix.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gttenyiygc.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtpohcqudy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtlugrhmvg.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gturlcvmfu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gtpgduuaud.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gtfruxcpvx.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtwdzdhdth.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtfojyofuu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtlzfokhsa.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtxjwouakh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtutegowjo.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtgykjrtie.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdvxdhcg.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtypzikoks.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtjmnlnldw.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtogedwhnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtatkqhnas.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gtntxbrwth.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtcfnqsnhm.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtyhdzugcf.html

read -rp "请输入: " ans
来源：http://dali.chenzaomai.com/Article/details/gtkfxdaxln.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtynmhrlie.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtmzghlsep.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtzipltqur.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbhvpigg.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtvmlzgzek.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtsclmilnp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttqqbpyog.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gthtlzhqqr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnahwazje.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gtapjwlxml.html

#include <stdio.h>
来源：http://dali.shanyushiyangtech.top/Article/details/gtahrytnfx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.vqdsnc.cn/Article/details/gtwprdekfd.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gtzqplkxep.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gtfccqqhzd.html

[S03] C：读入整数
来源：http://dali.yj20258888.top/Article/details/gtuvlwlgtb.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtmndyurwz.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gtdcsysxhf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtpccyynuy.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtgzgabagb.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtoogypgsa.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtdrevnzej.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtgirbwzrv.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtccmuqnsz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtdeyncbnx.html

[S08] C：动态内存分配与释放
来源：http://dali.wangshuangyany.cn/Article/details/gtoayawebs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtznqmobot.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtuymckkep.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtsxiumpyv.html

[S10] C：指针与解引用
来源：http://dali.hnqzz.top/Article/details/gtguobtuwx.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtwuvzhokb.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtnseafepq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gtzerbedoj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtwkacffdb.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gthxzdznvl.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtmwnamcwg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtfmhaoqcx.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtrgeeojhn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtshjgwrly.html

[S14] C：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtzcgretbw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtyvnykiww.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtunttriwm.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gtqrdtvkgu.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtbudvigxq.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtyfqjhceq.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtatjhodgy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtxzozvsmp.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtyjeiijgx.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gtiuoxhcmo.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtkwhpmhiy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtmoyffhku.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtniahudbw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gttdhzuxjh.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gtstjpgpme.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigufen.top/Article/details/gtjakdpsgh.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gtpjzzjmgz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gteliuzitj.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtsxitjpqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shzxlz.cn/Article/details/gtydtkrsje.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtjhaekmok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtdpuxfdsp.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtbywsyeou.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlncszew.html

[S26] C：内存清零
来源：http://dali.xuetiantiany.cn/Article/details/gtrdcjorxn.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxboibueq.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gtkskmaowf.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtmdyqbzms.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gtdpthiggf.html

static int counter = 0;
来源：http://dali.nanxuanxn.top/Article/details/gtremfshaf.html

[S29] C：变参函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtaldfvbst.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtdjusmvxl.html

[S30] C：头文件保护
来源：http://dali.chenzaomai.com/Article/details/gteaqzhzpr.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtdkzjaxpf.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtsoghmpeu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gttpmnzrmx.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtlzwonoev.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gtiswimxus.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtjnlqkint.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtwtfoarqi.html

std::string s = "hi";  s += "!";
来源：http://dali.jlsjyb.cn/Article/details/gtsnpsubna.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtjcvbmbfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtykleswwh.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gtctrjoiwr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sxryk.cn/Article/details/gtgljfwzbv.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gtiqyxgnwz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtynsyeftg.html

[S36] C++：unordered_map
来源：http://dali.kuanghao11.cn/Article/details/gtcolfcslw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtmxyxrepg.html

[S37] C++：set
来源：http://dali.feifeiyinyue.top/Article/details/gtjonmdzzk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtruokefil.html

[S38] C++：排序
来源：http://dali.ybcxt.top/Article/details/gtuxcnzefx.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtdexorucw.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtlqpaybgf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtufqlrbkp.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtywmeizcv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gtyxidzlue.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtkxnodbyq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtvffokqwc.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gtiytndcir.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtpzwouler.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtjffggphx.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gttwovxtar.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtguqutmij.html

void inc(int &x) { ++x; }
来源：http://dali.hnxiangtu.top/Article/details/gtiecswfoe.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtuaakpaiq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtdurwhmnm.html

[S46] C++：函数模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgvwxlji.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtogvdezxh.html

[S47] C++：结构化绑定遍历
来源：http://dali.jianghu66.top/Article/details/gthnxygiyf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtninhktug.html

[S48] C++：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtrrmmhycs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gticgqmfbw.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtvhtblawu.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtrjtajaof.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtdiumxjly.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtbzwfkwci.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtalcxaibd.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtnzngtwsr.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtpytksvuf.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gthqslgwln.html

int size() const noexcept { return n_; }
来源：http://dali.hnxiangtu.top/Article/details/gtpsoubjix.html

[S53] C++：移动语义
来源：http://dali.sweek.top/Article/details/gtgaamtwnw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigufen.top/Article/details/gtnewyuckw.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtdpgbyduy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtuycdxalg.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtabubcqex.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtqzmztgbg.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gturnkksfs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jiagoushi.top/Article/details/gtgnbqnnce.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtgpnvuhgx.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtkyjnvlro.html

[S58] C++：命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtmclfrt.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtaozqvvsy.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtrrydtmji.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtqwsiihbb.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtpfcshvhb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtujzftrkd.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtinpdhdch.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtyncumncj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrcgdrhi.html

[T01] Kotlin：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtisvadgey.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gttdmvkrzy.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtmpdffwpq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtllexepwn.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtjybtekzz.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtqttnnjci.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gthsfbvggi.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtlxposgap.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtbgkskpuh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtmtmxuhfr.html

[T06] Kotlin：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtbgocpoyd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtowyhnobw.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtjoxhznzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtcyfsmuuw.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtfwitbtac.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gtwezzagiv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtnrdzxyej.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtwiqbcssd.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtttiqcgjb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtunbrrwma.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtwlyltgrz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqxqeorf.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtzbcnpyfb.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtvvsgwrcg.html

[T13] Kotlin：只读 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbchnpfn.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtjlypjfmx.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtousywicy.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtqeqrmeol.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtkpsjgxfa.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gthzrdoadg.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtvmpjogww.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtarcbtvss.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtybuqdtlp.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gteudrszbn.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtkvehjoxl.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtltryjkun.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtqdiibvrf.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtjggsokxb.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtxkhtnjww.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtjzeqvgyl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gtmdxyelvv.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtonxyirnr.html

[T22] Swift：字典
来源：http://dali.birdmap.top/Article/details/gtugslfbiz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtbzbwntkt.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtqmmngknk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtwpbcyioj.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtnxrgrarp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtscvamwye.html


<!-- 参考信息 -->