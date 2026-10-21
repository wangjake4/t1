代发 wailian999

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtfrupdumo.html

[R22] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gtecsbundq.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gtcyzxaymd.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtcjfebfdv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtnrnysmfc.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtjehwnczz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zdqjudy.top/Article/details/gtgpwljyzs.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtxpknqlva.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtdukhsecw.html

[R26] 命令替换
来源：http://dali.tanke756.top/Article/details/gtbdcrjsbr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtkxgfdvbz.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gtfqwnoqko.html

echo $((1 + 2 * 3))
来源：http://dali.chenzaomai.com/Article/details/gtigobudfi.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtznvtkmkm.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gtowtjxygq.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtrqkslyun.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gthlohulrd.html

[R30] 函数返回状态码
来源：http://dali.yonumen.top/Article/details/gtyyecvqci.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtkijkvxnn.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtjhupgqde.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtdqzuxnqh.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtivsnpxlr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gtspvxmhlc.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtcusqhlzz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbpyzejf.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtyvcnhdge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtrwhbrsam.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtarzrywbh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtasyekiuk.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtafrvovxt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jlsjyb.cn/Article/details/gtxbxxsxvk.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gtvzqygoch.html

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtbjaxedrt.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtikhgvvzc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdjhnqff.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtjswlihlc.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtexhpemby.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtixvlcuzf.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtdlemzfpw.html

[R41] 丢弃输出
来源：http://dali.birdmap.top/Article/details/gtnvybrfsb.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtjnfsxwwj.html

[R42] 输入重定向
来源：http://dali.andypj.xyz/Article/details/gtzpjanrst.html

wc -l < a.txt
来源：http://dali.xuanzx.com/Article/details/gtqvtjufsp.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtoyqjbsar.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gtcagboyqf.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtfyshkcjt.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtalwowgam.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemjzgtqe.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gtzefelxdm.html

[R46] 递归替换文件内容
来源：http://dali.zhoulong.xyz/Article/details/gtoeyepdku.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.meibo888.top/Article/details/gtkbovfcsc.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gtjjqtquvb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtbjoraqis.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtjqaluols.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtjgzuujxa.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtdbqrqmmy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ehwqpu.com/Article/details/gtxemzjiis.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtjhycxrgy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gtotzlkfnp.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtptbmtiay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtutrgexly.html

[R52] 统计行数
来源：http://dali.birdmap.top/Article/details/gtiwkyanap.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtvnydkmxz.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtxjmpuakm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtoomgimfp.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gteqvwydyy.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtkklzvyna.html

[R55] 压缩与解压
来源：http://dali.jinqigufen.top/Article/details/gtsvhcutlx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtzpmtzdrq.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gttcldpwnu.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagqmggxa.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtrvstiqwe.html

ssh user@host 'uptime'
来源：http://dali.redwolf501.top/Article/details/gtzpiddolz.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gthqtgockl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtjpinxxsq.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtriuiwsxq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuetiantiany.cn/Article/details/gtcjhgtzuo.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtakekdjmk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtnogzrknm.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtrflpsqbi.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtapxynnbl.html

[R62] 找最占空间的文件
来源：http://dali.dianchejie.cn/Article/details/gtrrqhdcpy.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfrhaoll.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtypdedirx.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gtckxahmmd.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtgztdmauy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnqzz.top/Article/details/gtloahheuc.html

[R65] 查看端口占用
来源：http://dali.shangyingyoupin.top/Article/details/gtskaqktjh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.0kj1m.cn/Article/details/gtxdieztth.html

[R66] 定时任务
来源：http://dali.sufxvd.cn/Article/details/gtwubgkyoq.html

crontab -e;  crontab -l
来源：http://dali.meibo888.top/Article/details/gtzvzsbxlb.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gteklieejl.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtpekhitms.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtfsuavfzm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtsrrtgtae.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtgapsxwst.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtmjgnurnm.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtxaextzqm.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gttsvvwksj.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtojrvlmko.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtibcyllup.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtjferrocy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gttyzdfwxs.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtmsbpqquq.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtpjylpbcl.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtnfsoetqk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtveqjzsjy.html

[R75] 导出环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsjzqshl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtcwnkcvfj.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtqynzjxee.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtngtbjbzj.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtiqlfkrca.html

read -rp "请输入: " ans
来源：http://dali.zhongyouzk.top/Article/details/gtznfyfuqk.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtgqnihymw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.mhx1999.top/Article/details/gtezbftpsw.html

[R79] 解析命令行选项
来源：http://dali.mhx1999.top/Article/details/gtinigeokg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.meibo888.top/Article/details/gtxnyhszss.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtdkrnamgy.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtyajyqtxr.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtynzftcnc.html

S. C / C++ 专题
来源：http://dali.jinqigufen.top/Article/details/gtmxgmyyun.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnxkbuzkz.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtmpwmghnn.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gtqpejhcpl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtrtgpetfy.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gttdyjrjsk.html

int a = 10; printf("%d\n", a);
来源：http://dali.cqqwz.cn/Article/details/gtptyoskow.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtfeyfttnl.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtjhrlxiir.html

[S04] C：字符串复制
来源：http://dali.gotoacloud.top/Article/details/gtmkfppngk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtwitbjzcf.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtcbuntiuu.html

strlen(s)
来源：http://dali.cheryme.top/Article/details/gtucwujhdn.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtgpkufjjl.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gtrnvoahfy.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtjoivekvk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtqlebqhma.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtmskwjyxo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gtztfteubu.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtavjfgtkk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gtjrutcefc.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtxenidybz.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtjribidjp.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gthqpcolor.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gtrtrsigxh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtxvpqdjxf.html

fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gthkukltzx.html

[S12] C：写文件
来源：http://dali.havefunace.top/Article/details/gtulquktqm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfifpoqo.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gtxuzgjdfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtlpblsewj.html

[S14] C：枚举
来源：http://dali.yuxming.cn/Article/details/gtguyreshz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gthjrmkuuq.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtcvvafpxl.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtleuirqjx.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtvurmvsun.html

x |= (1 << 3);
来源：http://dali.hywenlv.cn/Article/details/gtmdzyaqyi.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtmrezvnim.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtrsuhveri.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtsxyxqwfs.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtrqcdzzyk.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtsdykkqhl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtyghdebcj.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtvkwkpgve.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gtoeomqyeu.html

[S21] C：字符类别判断
来源：http://dali.yangfankeji.com/Article/details/gtatfbxqmr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gthzmfahdt.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtycnhyybk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtwioggefu.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtokzugtwp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtwhvpcqio.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtpmzujobs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtaatwhcba.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtpddvhwsk.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtrchkfziy.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzogkgyui.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtaqbeejiq.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gttmrkpwhq.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtswhghmoz.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtakmyzljg.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtnjfcdjni.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtecgyxnro.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtvzloeqcc.html

[S30] C：头文件保护
来源：http://dali.hysaishi.cn/Article/details/gtgbvbogvg.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtzqasyysh.html

#define X_H
来源：http://dali.iojbl.cn/Article/details/gtroyddkfb.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtxbfsfptf.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtuafqeduu.html

#include <iostream>
来源：http://dali.yj202588.top/Article/details/gtzdeeyefg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtkodisfby.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtfmrlydwn.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtjxwnuqrk.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvmfaydn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtawrxzavk.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtrxptlzqy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.0kj1m.cn/Article/details/gtlxqpvutj.html

[S35] C++：map
来源：http://dali.cdnleiting.top/Article/details/gtualyvnkn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gttaetyseq.html

[S36] C++：unordered_map
来源：http://dali.snrcjt.cn/Article/details/gtivcaaeaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtzosxhytj.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtlgtwjcpa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtwubkvzuy.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtonqzvkdu.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtzdfuhlwx.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gtccvirrgg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsfkbhuw.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtivqfquze.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtpwhpwhds.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtxyyvauig.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtlgvhqwuj.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtyupgkjst.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtegluanls.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtntcfelno.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjpbmnbh.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gtmsuzgvxq.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtaslomcbp.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtxftupgzm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtgijiqpmx.html

[S46] C++：函数模板
来源：http://dali.snrcjt.cn/Article/details/gtgeeudawv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtoyzutgdt.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtozacqdwp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtbqjionle.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gttvbnleku.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtgpjokett.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gttazmrhfo.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gteabwoylg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtpijaellf.html

[S50] C++：格式化数字
来源：http://dali.jianghu66.top/Article/details/gtzfnmmcrn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtnmkoxekv.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtjggsehza.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gtbeezgxxn.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtqjoecitu.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtznegysqo.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtxpaugdyo.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtwkzzmtga.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtazpenxtt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtngwvwsnz.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtvqkxjuzn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtwhkqhclb.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtaofjnspj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsikhdlit.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtdlumqttb.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtpjygnjwo.html

[S58] C++：命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtoljhkrpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gtgjqkulfe.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtamsfetpb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtryglcdjh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxtztzfr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtuwrpvkoo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwwtxrgfq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtugnteemv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflcvenct.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtienytgaw.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtrgdixssc.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gtrbtnoqxy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtjeozjyrt.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtpfmzrmsb.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaojovou.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtihntvfic.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gteleshnrq.html

[T05] Kotlin：when 表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtupoutvww.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtnxtajcmt.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtakfgnfpm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtrhmvzkhc.html

[T07] Kotlin：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtbtxynkbc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hywenlv.cn/Article/details/gtggpfdpzv.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtsuuwcfqn.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtgtgbmloq.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtjcuhifef.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtumofojnf.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtxmwofoba.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhixingplan.top/Article/details/gtaoynmcqh.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gtmflkjubh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtumuqztio.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtxfzzithc.html

val (a, b) = Pair(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtwexeirfn.html

[T13] Kotlin：只读 Map
来源：http://dali.kuanghao11.cn/Article/details/gtqxmdnkas.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gtfmsyzjwu.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtpptuletp.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtqlwgmalb.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gthjwgvnlf.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtojtwqktd.html

[T16] Swift：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtplzzhukg.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtrhdydnkg.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtbhzmmhyh.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtbhmzbthn.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtitajpkdf.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtuadcmiwk.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtgoemcaix.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtxinlythl.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtbriqabpq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuanzx.com/Article/details/gtelzlojdp.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtzdavopbn.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gtndyyugdw.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtkbycdwad.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtffwnorzn.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtmlidogmu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtqjnwwymw.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtphlkenil.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gtbevtqlwz.html


<!-- 参考信息 -->