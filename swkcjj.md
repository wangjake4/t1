代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtjpzbwpuh.html

[R14] C 风格 for
来源：http://dali.gzhubu.top/Article/details/gtzjrrrhvu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtidtlwibr.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtwgkvetje.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtsyroalec.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gtbvkfdgoj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cucudq.cn/Article/details/gtlvojkchl.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtneasmfey.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtueynyfxl.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtwyjxllwl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pycfn.com/Article/details/gtccazixca.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtnhhepmsr.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhwnhzsn.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gthkofjbdh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtvlsnmvfc.html

[R21] 字符串长度
来源：http://dali.daria6918.cn/Article/details/gtxyyeoans.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtnzcmlssx.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtnuduvvwc.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtyjplirya.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtcbhmqeql.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtkaziiicw.html

[R24] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtwasbshtt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xinyue.icu/Article/details/gtqdacjubw.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtvbjdefxo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtfefwmswe.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtzzgibknd.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtftejfulo.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtjlulnkfm.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gtobxhuiap.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtublfhvhu.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtvajehtzz.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtlxyhgeoa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtmcjkrrlc.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtbidxbige.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtcjcdjlks.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtvgxldrng.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtcaifulpf.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gtamptllgj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmartvct.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtjduelnmw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrueixwnv.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gttdsowgep.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtozwvkpwb.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gthesgwxas.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtfpdzoipg.html

[R36] 并发执行多个任务
来源：http://dali.yvedp.cn/Article/details/gtouofhcin.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gthgbcwpph.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtktvtzqah.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtdmlcelsb.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gtctqijrsw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtyftbhxll.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtsaaxthan.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gtpajqoeqm.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gtaoalgvip.html

echo "log" >> out.log
来源：http://dali.tian-w.cn/Article/details/gtibdphlkb.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gteehigwta.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtwnyoolxn.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtzxdhpiub.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtjzyozfzx.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtjqiczcft.html

find . -name "*.log" -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfcmpsou.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtnstcggos.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtdqlnivdi.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gtqjohwocy.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtzpgjfebm.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtsaawaebo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtsqzindek.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtjhjkeqnt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtjbzpulqr.html

[R48] awk 取指定列
来源：http://dali.iojbl.cn/Article/details/gtcglcfdbu.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtsjoyxpzh.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gtzzyfwmzk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtfthnjqcb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtgezagcsx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtfyjxtygc.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gtdhmxsuwt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtrmyzhwsa.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtryvetcwj.html

wc -l a.txt
来源：http://dali.yangfankeji.com/Article/details/gtcljrvgdv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gtdganztdi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtwpwmkbmu.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtydymllta.html

diff a.txt b.txt
来源：http://dali.hnqzz.top/Article/details/gtvnsjmnhg.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtckbgefqn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtkrysniez.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtlpshhxnw.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtmieorpqg.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtrcebftmj.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtosdlwhpv.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gtkizwvnhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtouftrhdy.html

[R59] 发 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtqngrwdnj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gttxhkcgff.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtdivdwldv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtezcpgmmi.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtojogwuzd.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtpzzitcru.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtolbkrcak.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtlixdqshs.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtatbykkzy.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtparpyhsb.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gttkzyuobu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtouscgolr.html

[R65] 查看端口占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmslotdw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwakedsw.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gtezhbedui.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtyxfwxldb.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtkpmofbpe.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtdlvnrlen.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gthdulgysl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagnvkrsc.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtleascqhx.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtapinluqm.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqjepryc.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtcvjqeqor.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtforzscyl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtjbrhuoad.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtccwqnyae.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtjoctvhlc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtwmwthcra.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtslgmwvaw.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtktkpwncn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gtrzkybzqm.html

[R75] 导出环境变量
来源：http://dali.svipenyu.cn/Article/details/gtczelehgb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtxdaanmqs.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtyhrlbcqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yvedp.cn/Article/details/gtxstoztey.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtpuefsfzs.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gthkfumlup.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtuhfuouza.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtcpqouiwe.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtfsefmogc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cucudq.cn/Article/details/gtebusvgzw.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gthlcghpct.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtsirlntvl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrspvixbk.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtdrtmabse.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkfzmirwl.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtgjynenvm.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtvafknhyw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtlvecjmex.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtqwrpwdtp.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtzlobuhjk.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtmhaljsbw.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gtbzovxoio.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtdvznvswv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtqbunwjdv.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtbetzqjeq.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gttkuhsqfm.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtcufbryid.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtntyiizre.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtejvjdfdh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtoxeghhec.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtwcqcvgul.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guowangkeji.top/Article/details/gthfkqukgl.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtdxvbhhbm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtoriyyayo.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gtyojyxydt.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtbotyczch.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtbjgcyjee.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtmwzbxtdh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtujvyiamr.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtqtdmimbg.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtlypgsvoa.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtycayguaa.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtpljznjux.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtuvvsuyeu.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtqhtzaciz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtpzwfjxoo.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gtxpkspvyh.html

(double) a / b
来源：http://dali.cashguo.top/Article/details/gtphtsglqk.html

[S16] C：位操作置位
来源：http://dali.yuxming.cn/Article/details/gtfbkaednb.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtgonpcdyw.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtzpralhtu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtxhcvirkj.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtidqachfx.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtrplgcnei.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtfdlnphzf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtdphrwcmn.html

[S20] C：二分查找
来源：http://dali.vqdsnc.cn/Article/details/gtrwrewcqc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtbqhtzvjt.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gtezgiujcc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtifheoaeh.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gthnwpyxdv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtypdtkrww.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtfcdhtskl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtymwhgplu.html

[S24] C：获取本地时间
来源：http://dali.sxryk.cn/Article/details/gtgedsbbqj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xylfe.cn/Article/details/gthfkmsbeq.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmcyyzai.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gtumifvgyv.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtrixxgohc.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtsfygxjka.html

[S27] C：定义常量
来源：http://dali.tianlin.xyz/Article/details/gtzzfjzpxk.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtenswhhhi.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtbpqxjhnj.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtrmzftjog.html

[S29] C：变参函数
来源：http://dali.ppjwa.cn/Article/details/gtlbhpliyk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtwtpptfxz.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtvtywqpgf.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtybdhvmdb.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyrrkjvp.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtwxufcdrn.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtlgtohdkf.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtrefjtszv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gtqungyxkk.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtlxfnxvbq.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtinqtypdi.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtkvzvesjd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yanxiufei.cn/Article/details/gtkppfzcks.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtrwcwmacu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtpqjlgrch.html

[S35] C++：map
来源：http://dali.hfpthk.cn/Article/details/gttnaexjxs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtriplaimp.html

[S36] C++：unordered_map
来源：http://dali.yonumen.top/Article/details/gtsaousgaw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtmucrjxmp.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtpclpuiaq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmcwflnz.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtmlqnkejf.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gtccdrogce.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtbooupedu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtiymmjehd.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gteuijiqpw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtdioctmqq.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtllnefwzy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gthpcfhpoe.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtdaszwgsk.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaueqajo.html

[S43] C++：智能指针
来源：http://dali.chenlongwang.top/Article/details/gtfoavqldu.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtunvwlusb.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtuwcqjthf.html

void inc(int &x) { ++x; }
来源：http://dali.redwolf501.top/Article/details/gttjwvlgey.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtdggyqiqd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtezckoaua.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gtsbfcppna.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hysaishi.cn/Article/details/gtuopylthy.html

[S47] C++：结构化绑定遍历
来源：http://dali.yueranfly.top/Article/details/gtebsvotzv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtslbzkbuj.html

[S48] C++：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtemnwqwtn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtetywnjpj.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtggooprhs.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtjatbkrue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gtmaxsdyop.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtsnxxjpqa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtujubfgms.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtovlrwcwy.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gterhudkoy.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtywnqyutd.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtnkvbpcyh.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtrkvooqjz.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gtpmdkxkeq.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxsqfato.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gttxfhhslq.html

[S55] C++：结构化绑定
来源：http://dali.cdnleiting.top/Article/details/gtizdxykxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtpkjzsrtl.html

[S56] C++：optional
来源：http://dali.svipenyu.cn/Article/details/gthlkrfzmh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.meibo888.top/Article/details/gtzqyjgvvc.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtdwckrozv.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtckimwsbq.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gteqeeplzb.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltjrcyoh.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gthkuoaqbj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtzaxpiyie.html

[S60] C++：遍历并删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtpyeevjht.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtnojggoet.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtltlrecbs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtyaqwaiyw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyntvscjd.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtgtqixcdv.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtnpyiswwf.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gtvhbxxsiv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtgblpidfw.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtehzoezwu.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmjkpkmp.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gtvufnvuel.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtxwetaymy.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtjufiypxl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtmmegbost.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjocxdgp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapgxvijy.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtsywqjcfu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtcrzzeioc.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtwyquoonm.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofrigirt.html

[T09] Kotlin：扩展函数
来源：http://dali.wangdashe.top/Article/details/gtjlbvrfog.html

fun String.exclaim() = this + "!"
来源：http://dali.yuxming.cn/Article/details/gtuhcskauy.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtmtgrpxvt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj202588.top/Article/details/gthzbqgvzt.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtcfiqszpl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gtmiwdgras.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtdbihmlyn.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtdhkkgtae.html

[T13] Kotlin：只读 Map
来源：http://dali.sweek.top/Article/details/gtwpdrqgns.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtntqvnebd.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gttxxeldbc.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gtypogofup.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtmrjrccqa.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtlrpeiwur.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtndnqflsk.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtgduvlfnz.html


<!-- 参考信息 -->