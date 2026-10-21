代发 wailian999

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gthqixbmtl.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtbtnkpggb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtsjjcsbkt.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gtaqxgkoaz.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gthoglyici.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtnhskqchs.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtzxbqflgp.html

[R23] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzolcsvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtanhhornp.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtngwuuvaz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.guannengcc.top/Article/details/gtuxvlcisa.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtyxgcuzja.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtwihmdjti.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtywtkrfdk.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzykyiik.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gthxvopsoq.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtxhghsnfv.html

[R28] 浮点运算
来源：http://dali.yangfankeji.com/Article/details/gtleddbwnw.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuxming.cn/Article/details/gtsyzsyakk.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtggsfmuzt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtkuoaljbx.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gtgoutploh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtiavztegu.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtgmklbywn.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtqpfscstx.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtmgqdtgkp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtcdkxfcxm.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtpoeacjaf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtanicykmw.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtdwilijci.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtlyzuhafc.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtvswwgttw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtdcpzobdh.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtxmvnvphz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gthebbxgnn.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtczyeexdd.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtsblmxzlr.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtpcnmoehz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gthaqfihuc.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtjuuwayaa.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtbhvpfhfp.html

[R40] 追加写日志
来源：http://dali.ehwqpu.com/Article/details/gtmsbilbjl.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtctulbabb.html

[R41] 丢弃输出
来源：http://dali.jiagoushi.top/Article/details/gtlljjiadv.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtrfpgugsk.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtsbcuxpvq.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtzdfiuwex.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtohnudxdr.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gtwlffbbhh.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtvypqyorz.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtwaxmbdvm.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gteeebjspg.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtzknixmwo.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtnuijyjtw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sufxvd.cn/Article/details/gtfbhksurp.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gteerofgkx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtchernmyy.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtwafgphgu.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtkmqukxvb.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtsarufvbi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtnhhlwxcf.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtwdbnqtov.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gthadvbzcl.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gttzbbveqf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gthnhujmpf.html

[R52] 统计行数
来源：http://dali.fzhhl.top/Article/details/gtgnamzwpk.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtrdmtfilz.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtavrjtbyu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gtsqzptjun.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gttmnvugyj.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gtwtxicwso.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gtzvevmyaj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtwsmpmnfo.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtppakoqyn.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtxujxcdlj.html

[R57] 远程执行命令
来源：http://dali.9152youxi.cn/Article/details/gtgnaeqzmp.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtrptwiygu.html

[R58] 下载文件
来源：http://dali.xuanzx.com/Article/details/gthbvtpzlr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtfgllrihy.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gtnbnlvnri.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtqmwrasbb.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezwxtlku.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtfssxbggr.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtqifwhvlw.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtvnkekcst.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtcxpdylre.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gtscfbjhlm.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gttersacgv.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtltpqsemj.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljdzstgy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gtspyhinwe.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtnsjjagnp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtucxxbuoz.html

[R66] 定时任务
来源：http://dali.dianchejie.cn/Article/details/gtpoufanrl.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtxzhntmpb.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtwlxvzdai.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtqnvbqhtc.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtnsgrjtex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtiiimajzn.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtznuwicfn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtfnsrtatf.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtxneucigf.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gtghigjghj.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtmkzxxkbq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtduasbzwl.html

[R72] 等待端口就绪
来源：http://dali.ydzc1.top/Article/details/gtpeofevft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtmqybbbnw.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtqaruorsq.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtfdgsxduy.html

[R74] 批量重命名
来源：http://dali.yueranfly.top/Article/details/gtptwqizal.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphzaecha.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtknmjdmov.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtfneqygom.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtyyslhdmi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtxbxhgvip.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gttisyekvp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtyafhxrhc.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkpjklcy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gtliqmprpk.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtcalptfky.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gthewzeozb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtxdfyeysy.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtlcxkigos.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtsbltqihv.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtuunuoyxg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzjoftvfy.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtuhgsqykz.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtsexzhrch.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gtkwlsjzoq.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gtxrnmiwml.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtanasykpt.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtpcuslcko.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtjcpsqzwz.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gthtqsrpzr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtxnlqiarp.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtxbemrrqy.html

strlen(s)
来源：http://dali.xylfe.cn/Article/details/gtipqozfvn.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtwkyijeeg.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtzsoortdp.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtdccilpth.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.smart0.xyz/Article/details/gtfroougew.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtzrrmssqb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtnpsbkweq.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gthmwtbged.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtwjvdzuly.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtacfntrpl.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtsxfhjpvr.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtqnclhyho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzajcjvph.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtoztnzphh.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtcyuevqno.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtuuxdywmi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtigwouspc.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtnbwjynjt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtvbpyljgf.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtwisgnecr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtcqhohgft.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gttwwhbjqb.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtpsvdyfyz.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtwwgygwrb.html

x |= (1 << 3);
来源：http://dali.aizwys.cn/Article/details/gtiubvgxxy.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gttaurhwmr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ivvv.top/Article/details/gtyvhmahvo.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtkakkamoo.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gtkekeuhtq.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtqnqradvg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtfteckkkh.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gthmuzhcyv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtnxhsknax.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulejfjkl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtjotwpcjn.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtfxjtsjoy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcplxywk.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtlpvuinhy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtyuywwhal.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtlmubhnny.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtgdmrkioa.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtihfovhwx.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtvkobojhk.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtayvciaqg.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtifhipmsv.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtveocupho.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtcwbscjoh.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtjrgblqjw.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtasxoauja.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtwvffxrud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gtduklejry.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtsgudqmha.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtmvlopmqu.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrxhlsay.html

#endif
来源：http://dali.sysykeji.top/Article/details/gtekufthjj.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtzesqiaeo.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtzteckzun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtvzfybklf.html

[S32] C++：字符串
来源：http://dali.guowangkeji.top/Article/details/gtrbhksiht.html

std::string s = "hi";  s += "!";
来源：http://dali.smart0.xyz/Article/details/gtmdfnzevm.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gttjtjxrvj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtoahdnsmq.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtsvqvdqze.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtofxyrkid.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gtcdvcqwyp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtfottvwfq.html

[S36] C++：unordered_map
来源：http://dali.nanxinkj.top/Article/details/gtghywitsy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtrdizomoh.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtzcfqgbud.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtjnrkkudo.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtrnkauxdi.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtwzswfioh.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gtyvqwnutu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj202588.top/Article/details/gtdefzijis.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gtnbcynclw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gtoiwazuoy.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngynzvmu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtcvibhsbm.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gthgkzynfy.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gthnxdymcz.html

[S43] C++：智能指针
来源：http://dali.gaohongyu789.top/Article/details/gtuetxlwis.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtgaecqwmq.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtllckkcpo.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtxbhwsctl.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtdeyieony.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtspiobqeg.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtgrzxjlvx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtnahyerhk.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtwjymnnrh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnprzxvva.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtpdywckkp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gthzxzojql.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtnhsjtqhe.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtxshbmhrs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gtdxeswlvg.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtwlpitetq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtrnjcnyku.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gtdrzvmgja.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtzwtvsesc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhixingplan.top/Article/details/gtpojxaqyv.html

int size() const noexcept { return n_; }
来源：http://dali.tian-w.cn/Article/details/gtobgmdhox.html

[S53] C++：移动语义
来源：http://dali.chenjidiqi.icu/Article/details/gtvrhhhtyo.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtspxehhls.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtueqvcyqa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtdjkvmkeq.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtsnxgyucg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.tian-w.cn/Article/details/gtyqxkqqet.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtnsmasiwf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtrulvmiht.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gterxgkvmg.html

constexpr int N = 10;
来源：http://dali.xziqi.cn/Article/details/gtbllgjspp.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtdrqfkjqf.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtqdnpycsn.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtdofudjdm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtbdzrvgya.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtfndnyngd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtzgflgqla.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvstyykne.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gthkcyjxvr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwubhusyj.html

[T01] Kotlin：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gttgmhtohp.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtbhbchycf.html

[T02] Kotlin：变量
来源：http://dali.nanxinkj.top/Article/details/gtesoojwxh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtekncuqtv.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgufenzy.top/Article/details/gtuwankyyi.html

"值: $b"
来源：http://dali.316326.xyz/Article/details/gtceyxwblq.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gtqjmzhufd.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gtzthxlegr.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtspvxogcr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gtsejvslcq.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtnsyzynsb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtglfjqnlv.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gthfyctgnn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xinyue.icu/Article/details/gtxlzohhac.html

[T08] Kotlin：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtsdddveui.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtuykagkye.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotjaizoc.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtjwyteyre.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtjvswofkn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtjqciuhta.html

[T11] Kotlin：协程
来源：http://dali.sufxvd.cn/Article/details/gtueszyyis.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtgyuxovoc.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gtdpzmgspd.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtsnqwzofi.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gtuapmxiys.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gthanvjqif.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtxnrsfwgy.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtatfrcujm.html

[T15] Kotlin：接口
来源：http://dali.dianchejie.cn/Article/details/gtovfcsxby.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtuhjyxbfe.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtmgsoammo.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtkptlshnl.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtugajvqcx.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtsmprlhcn.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtnhaasyvz.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqjbhoxo.html

[T19] Swift：可选绑定
来源：http://dali.yvedp.cn/Article/details/gtlmzkzsml.html

if let n = opt { print(n) }
来源：http://dali.smart0.xyz/Article/details/gtobwkkygp.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtfbyjavnc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtfbgnropy.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtmbqfshbo.html

for x in a { print(x) }
来源：http://dali.yvedp.cn/Article/details/gtypgzxzgz.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtqliicnnb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtbxmuvryh.html


<!-- 参考信息 -->