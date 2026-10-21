代发 wailian999

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtycxkzqns.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtkognxglv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gtnjkaazin.html

[R15] while 逐行读文件
来源：http://dali.316326.xyz/Article/details/gttvhivjfa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtlltymcyi.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtugajukih.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtclibaxkd.html

[R17] 数组定义与取值
来源：http://dali.jqgufenzy.top/Article/details/gtcjwtfaab.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258888.top/Article/details/gtszxqynyz.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtibtbgmpe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtzukpugdk.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtydqxxcvh.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtfwlwgxiw.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtqkswliqu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ivvv.top/Article/details/gtcywehyho.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gtgpvueuxh.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtoqxfmzdf.html

[R22] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtmzmymffm.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtdcinpgeu.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtenkvoqjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtsdushjpy.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtgvrpkezz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gtwoutvpdd.html

[R25] 去后缀 / 去前缀
来源：http://dali.hywenlv.cn/Article/details/gtdiwzelke.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gtuerqxgox.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtaoxadiit.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtzivsclyk.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtvbzniusj.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtbrumsdwy.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtactdgrea.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtcwlsncov.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtymeznagl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gtojxbfcij.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gttecaxcrk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtaqvdleaj.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gthvupymlu.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gtsenvxjcb.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtifkhupeb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtgxtfpzcl.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtbfnggbao.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtlwcrwncu.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtgwwsfvem.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtwmdgfhcy.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gthtktlizo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtuwmlwzvp.html

[R36] 并发执行多个任务
来源：http://dali.feifeiyinyue.top/Article/details/gttezxecrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.iojbl.cn/Article/details/gthixrrzpc.html

[R37] 把输出赋给变量
来源：http://dali.ydzc1.top/Article/details/gtgfwrdyyn.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtxhjadxph.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtltwyjsyg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbxjhumx.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtywekqtty.html

cmd > out.log 2>&1
来源：http://dali.ehwqpu.com/Article/details/gtfxieadkv.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gtavckydjc.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtgjrsllws.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gtvwgdmveg.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtnmnpeaaq.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtfqjynwur.html

wc -l < a.txt
来源：http://dali.sysykeji.top/Article/details/gtxvxxqkcn.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtzotfbyaa.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtghhxbirz.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gttraixyzh.html

find . -mtime -7 -type f
来源：http://dali.hywenlv.cn/Article/details/gtrqzmqqdr.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtwwdkessk.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gtlnkoivji.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtkyyzeqgt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtdrxxikuu.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gtydxjzngn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtcxqyqncn.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gteaszyslq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtjmhmslat.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gtugdxdvii.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gtymycsumt.html

[R50] awk 求和
来源：http://dali.guowangkeji.top/Article/details/gtyqfllhdl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtlkhgzesn.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlvwmvcd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtyzleuuow.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gtyvpjcwrk.html

wc -l a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtcjkotnvr.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtergxjuif.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqtbxyxs.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtqppvokdp.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtawumsafl.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtswobjdir.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtveozgkho.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtkgdfhpqu.html

scp file user@host:/path/
来源：http://dali.yongpay.top/Article/details/gtambuxhwa.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gthwhifajf.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtkbtvvgql.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtjdeqmeav.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtfcclyxom.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtsndoknlq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuanzhike.top/Article/details/gtiumtcvpy.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtixpmlhqd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtodlraire.html

[R61] 磁盘占用
来源：http://dali.pengpengdd.cyou/Article/details/gtjkqbzcbr.html

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gtisfhukmo.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtquzfjvjq.html

du -ah . | sort -rh | head -10
来源：http://dali.ybcxt.top/Article/details/gtptmscode.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gtrwepusht.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtlwkztehy.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtgoznvorq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.feifeiyinyue.top/Article/details/gtrnwoitkn.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtsgyctutc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gtaxijdtxr.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtvfjhhztp.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtpjcguakj.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gtosplxbvf.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gttcvvvtlh.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gthysvdlvt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gtortdlwrf.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtoqmmytpw.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtihhtbyzb.html

[R70] 时间戳与互转
来源：http://dali.guowangkeji.top/Article/details/gtdgebjayg.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtxgyssbed.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtxxdqicwi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtlytauclz.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtxsjesyah.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gteodqcpll.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtvfsvukcv.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtfmopighc.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtlosyusmo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gtjsvatwui.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtevvadzus.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtamwdjcsm.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtialgtukn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtibbqrhdk.html

[R77] 读取用户输入
来源：http://dali.yvedp.cn/Article/details/gthyevjcfk.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtrlnioaqp.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtgxwvqnlw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtojasklkh.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gthoiogqdi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtyprslewb.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gttmarxxba.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtlxtbsyvc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqiifoohn.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gtlvnqguuo.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgebpmpgw.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtslhtjfak.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtaxcdzjfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtsvokiwbs.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtxqcioiep.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtlqtewday.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gtlmiqimnl.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhjgzioc.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtdyfhyhmn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtlrrjdkse.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gthpbngybg.html

strlen(s)
来源：http://dali.jlsjyb.cn/Article/details/gthqiwvzqb.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtrwtbmehv.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanshfhwp.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtgzpvrbej.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtdbokxxou.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtsminglhw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgufenzy.top/Article/details/gtptbwicud.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gtoktekwal.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gthetujcdv.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtzdrrehzi.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtisjjkwie.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtoenibqqy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gtnhaqhmvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtcchbsvhd.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtuytibenx.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtlwejmhpb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtazpzrega.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtqdsbmzxx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtcezvptdx.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtmjslcfgy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gtcfbdxscs.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvdwlbmr.html

(double) a / b
来源：http://dali.yongpay.top/Article/details/gtgnajjoie.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gthrqaqvei.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtsajzcvkl.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpootfftb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fzhhl.top/Article/details/gtdluxqcgm.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gttswxzkin.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gtlejlayoy.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtszbikeea.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtlfbncjki.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtghkczven.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtxrxuhlsn.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtimmvautn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenlongwang.top/Article/details/gtoytmbnot.html

[S22] C：字符串转数字
来源：http://dali.zycfv.cn/Article/details/gtrdhkdcry.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtwzdoejmq.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtgpdheopt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtqyrvhkax.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtvoupazge.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gtzjgxpdnq.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtfxrqlsxk.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtclzsgipt.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gtsgmjwvgp.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gttofjulli.html

[S27] C：定义常量
来源：http://dali.dianchejie.cn/Article/details/gtmazfetpv.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtjxnjrmml.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtomdvqrsy.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtijjlbsiq.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmltkrdp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtrsoaclos.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtupeyhcad.html

#ifndef X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtceynljpb.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtoxlmnnqq.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gtaaaklxyp.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtlzmqsryk.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtrzqmifqv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gthawdlgii.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtopibikge.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtouhbbbwb.html

[S33] C++：vector 增删
来源：http://dali.sxryk.cn/Article/details/gtmyfwthvt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gttfzhbqcp.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtvaoivtrt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtqodnmuex.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gtntunlcbk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtzvoxafrf.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtgmxuhqzf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtyoaatlvd.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gtguwfkijl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangdashe.top/Article/details/gtccsqklgw.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtoqbgfwuo.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtxyydvgbo.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtgpizjljv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtubtheorf.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtgmeyoivv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtuhygwadb.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtdjxytjzk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jlsjyb.cn/Article/details/gttlouqxhu.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldvhazwy.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvlvvniq.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gtzspbuber.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtfmtfhlmc.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gtrnarerqu.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtdgfvcccv.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtycrkviqv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnstqcbpu.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtnbgzzsos.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtcgrlllix.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtxufsxwxx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtkxxeiiwx.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtupgeqkkb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtxgyqlofp.html

while (std::getline(in, line)) { }
来源：http://dali.yuxming.cn/Article/details/gtjkrqscfj.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtoeupmqqk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtjxwcsbxw.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtbgaovysv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtvmymtepc.html

[S51] C++：显式类型转换
来源：http://dali.hnqzz.top/Article/details/gttppqwene.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gttcklrwcz.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxinkj.top/Article/details/gtvyombgok.html

int size() const noexcept { return n_; }
来源：http://dali.gzhubu.top/Article/details/gtkxopyqav.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtfggirsvp.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtrdppabbl.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtprmurxxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gttetitrcc.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtwslcngeq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtbphcugxg.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gtnaccfkas.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gthshxmhqo.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gthcasexen.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtdkazhiov.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gthmiescfg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gteyrqqyzp.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtodjhhvxt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtghzynann.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtuyivmcno.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtzokckcto.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttdnymrmp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtjdjenpvy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgzkxajfp.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtooykpyqj.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gtpwgumjfs.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtdgkydsqn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtjftuffes.html

[T03] Kotlin：字符串模板
来源：http://dali.hammf.cn/Article/details/gtzipitdjt.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtqzimwalh.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtnbbmcgxz.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtuvqiamad.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtbtvwwbmu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gthzjczoxh.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtsrxzaqms.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtdageboic.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtuduanpmq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtjwhhqgij.html

[T08] Kotlin：数据类
来源：http://dali.yangfankeji.com/Article/details/gthrybgrce.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtvijpshpw.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtzhzgekab.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gttrcyexrx.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtleiflenl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtqckazpre.html

[T11] Kotlin：协程
来源：http://dali.ivvv.top/Article/details/gtefwawrdx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtvsfnbtdd.html

[T12] Kotlin：解构声明
来源：http://dali.nanxinkj.top/Article/details/gtcqtitdnz.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtzyqczxrb.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtjjwkhfdw.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtnxznjwci.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqjetyau.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtvnlwffad.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtrgrkoddu.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtyxrmxijn.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtqlhpxdrw.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtbfzgzoil.html


<!-- 参考信息 -->