代发 wailian999

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gttuabdorm.html

[R16] until 等待条件
来源：http://dali.dianchejie.cn/Article/details/gtjdtmdtiq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtoytozlzb.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gtwtprxslu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtrbfhhdwu.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gtvuuzhjiw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenzaomai.com/Article/details/gtrvmpcyru.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtfeibftdv.html

echo "${#arr[@]}"
来源：http://dali.zhoulong.xyz/Article/details/gtgppukwye.html

[R20] 关联数组（字典）
来源：http://dali.dashuyun.cn/Article/details/gtiopaskpq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtrcdhacja.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gtmpcqkpqb.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtloapwdzs.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtyfslweud.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtfcmqosnz.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gteeyigjcn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gtpkukhzns.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtznpyndzo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtrfpyafht.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtqdjkldlg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtroullkiq.html

[R26] 命令替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzufkuihu.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gttybflwpz.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gtrzurbriv.html

echo $((1 + 2 * 3))
来源：http://dali.ehwqpu.com/Article/details/gtbdmtrnms.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtvzsubvtg.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtdhfjrfnp.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtbcxgpodb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtcshygfeq.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gttknjwkvj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gtywxkpool.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gttojqusqh.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtvajlnqdu.html

[R32] 参数个数校验
来源：http://dali.dashuyun.cn/Article/details/gtjkdxbbed.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtuuokkdsf.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtlwhnqcwc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gtbwwhibqi.html

[R34] 退出时清理
来源：http://dali.daxiang520.top/Article/details/gtxmboarge.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guowangkeji.top/Article/details/gtzjcdbjxk.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtahoxyxrz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllmjmqpa.html

[R36] 并发执行多个任务
来源：http://dali.nwbrower.top/Article/details/gtaarxisgo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtrjgugvav.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gtpjafxivr.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtticxyjtu.html

[R38] 管道串联
来源：http://dali.haohaochexian.top/Article/details/gtibvqgias.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gtqzwpjpvx.html

[R39] 重定向标准输出与错误
来源：http://dali.jiagoushi.top/Article/details/gtpdkvxwjd.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtdbzwnqgy.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtomforgre.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtcabuvhbw.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtxcpinypy.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtccmzegds.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtczgnhwuf.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gteqtasvll.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtywpzkmwk.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtuyuelgmf.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtmexznyjr.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtqfwcxhin.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gtozwmcske.html

find . -name "*.tmp" -delete
来源：http://dali.yuanzhike.top/Article/details/gtzpysxxzm.html

[R46] 递归替换文件内容
来源：http://dali.jianghu66.top/Article/details/gtbvxasvwf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtvnzfxbfi.html

[R47] sed 单行替换
来源：http://dali.jyoumei.cn/Article/details/gtjjwzhrdq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gtxgihbkpa.html

[R48] awk 取指定列
来源：http://dali.xuetiantiany.cn/Article/details/gthnqlbpua.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpjipjxs.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtyagziutf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtolaypdwe.html

[R50] awk 求和
来源：http://dali.sxryk.cn/Article/details/gtccutasgn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gteipweqjg.html

[R51] 排序去重取前几
来源：http://dali.svipenyu.cn/Article/details/gtzsxjjkmu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtmejuprbc.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtebqpoteo.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtpxwmqcnf.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtvbiatbav.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtlhfjvdyq.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtmdwzbkba.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilnexiat.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtlatacyrw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtwmlfxrri.html

[R56] 远程拷贝
来源：http://dali.hysaishi.cn/Article/details/gtlnrbvnbf.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtnfqcbcci.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtjuiplsjo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtjvkmdaym.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gttjygibdh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtkdollrgm.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gtbudqpycg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtmojxxadg.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtrrptjhdt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtyaqoghhl.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtpvpnztih.html

df -h;  du -sh *
来源：http://dali.hammf.cn/Article/details/gtsnuwcydy.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtrhlnsfaj.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtkqpucqgd.html

[R63] 内存与进程
来源：http://dali.ybcxt.top/Article/details/gtctfimpdr.html

free -h;  ps aux | grep nginx
来源：http://dali.ehwqpu.com/Article/details/gtyzacbqgm.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gtzisurxvn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtssvpvluf.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtnxqlgbfw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.9152youxi.cn/Article/details/gtknmebvxr.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtsgsatifv.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtimbteieo.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtucljnsoq.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtzsdffrxe.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gtdtawbbyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtvnedwkvf.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gtmeqmthfa.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtwvsrxbpg.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtfpoygojv.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtvpxwjama.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtfewssudc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtwvfcpdfk.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtuheewynl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtfbqpppty.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtskrxhhcb.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gthusbasdu.html

[R74] 批量重命名
来源：http://dali.gotoacloud.top/Article/details/gtyhhbyxyv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtgekflrcs.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtijkknush.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtssabndjj.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtfjqqbbuf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtptpzqvnd.html

[R77] 读取用户输入
来源：http://dali.gotoacloud.top/Article/details/gtznxrfcgg.html

read -rp "请输入: " ans
来源：http://dali.dashuyun.cn/Article/details/gtepkmqzkr.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtejztdnxq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtblyqtegr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtjczdjfnp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daria6918.cn/Article/details/gtvloryfwi.html

[R80] 查看脚本执行耗时
来源：http://dali.xuanzx.com/Article/details/gtmjcgteeb.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtjimpgqdx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtykpqsduw.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkailfvf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtepqhmzml.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtfwgmogyr.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtekccmtju.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gthkbopsbf.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtufevebnz.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtcfjuitri.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtbvjrpqen.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtlefcavfm.html

[S04] C：字符串复制
来源：http://dali.hfpthk.cn/Article/details/gtpmmdqpth.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrxmrfld.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gtpugbqjcu.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtxpyqcxpi.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gtueqhxlea.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gtpvornapb.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtubdejylm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tian-w.cn/Article/details/gtphaaeyuq.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtachxiadn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258.top/Article/details/gtttdrzzis.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtyuvvzrpv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gtbblkpadr.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtatqflbps.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdkilsmk.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtgjondxen.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtiwxxlpvw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjdwqtog.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovnygxij.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gthzixcddk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gttqhcwqyl.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gttlgwoylv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtsizxdecl.html

[S14] C：枚举
来源：http://dali.wangdashe.top/Article/details/gtnkpvukli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtujljbqwd.html

[S15] C：类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtkpriiidr.html

(double) a / b
来源：http://dali.aibaodan.cn/Article/details/gthzwpnotk.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtbgcnoxpx.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuatlxnz.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtqpdttgxt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.birdmap.top/Article/details/gtmkwvmfgi.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtkwqvxfxx.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtjziiukuw.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtxpuckous.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtstepukxr.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtipmcnibh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpnhcspe.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gttbgnhmap.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtycsohwal.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtsxilskii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtdscaawrs.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtatojpvwu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gtxetlmsdk.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtrqzvogur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtryghdmrb.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtmgeqjkbb.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gtepsskvrm.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxhwlsjb.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gtjkwcbdax.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gtzudtrcpf.html

const double PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtzmifbtjv.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtvwrsrdxx.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gthijfmmvg.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtowxuctmi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gtpvwozduo.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtuixevhlv.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtemfhntgv.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtycdhrizl.html

#endif
来源：http://dali.hammf.cn/Article/details/gtohdgexxm.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gttpfubbjb.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtaqutvjuk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.316326.xyz/Article/details/gtjwsnyllz.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtfmuhgivv.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtsbymqhgm.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtkxwgpryl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gthrnusmen.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtpjxcdokq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtgzfhxfpm.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtxijllrkk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtcynohmlt.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtyblhvfja.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtnbtjdghn.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gtqkovlttd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.0kj1m.cn/Article/details/gtnvzhavda.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtfpsgegfd.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtadscypeh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoqojbav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtnrbcokvn.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gtyuqmeplz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtnvrbcgbj.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gthwtdjjjl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtdutheola.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtaitbymlk.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtoeyklfkg.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gtphwxlyld.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtqidulpgb.html

[S44] C++：引用传参
来源：http://dali.zycfv.cn/Article/details/gtysvyhksd.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtmsivnqql.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtcgbboeqf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gotoacloud.top/Article/details/gtfrfnkmsi.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtskjkhnwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtcwkzzgmz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtknycmjeu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtdrjewnfl.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtnhzsasyz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.havefunace.top/Article/details/gtmwljbhpg.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtlwhgzybu.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtpbrwteju.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.dashuyun.cn/Article/details/gthqrqerbp.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtatqtmiwj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gtzndfhxqn.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtzmzplhbm.html

static_cast<double>(a) / b
来源：http://dali.meibo888.top/Article/details/gtytznlopu.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258.top/Article/details/gtccuctwoo.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtsllbjhcw.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtadtesige.html

std::vector<int> w = std::move(v);
来源：http://dali.chenzaomai.com/Article/details/gtojssecuu.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtdbszinky.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtiugrdlqh.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtsickhesc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtpcddnoer.html

[S56] C++：optional
来源：http://dali.zycfv.cn/Article/details/gtpgexzlnh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtubxqjisy.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtwfeosarx.html

constexpr int N = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxozwdiy.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gtxmbcgpbo.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtcjfafosc.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtgovmachh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gteshufpsy.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gtvfcfapfi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtixmgzrih.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdotfyuqh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtvvtraveg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtujpyeraz.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gttlnlrudd.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtpxwrrqkd.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtosxjzccm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.havefunace.top/Article/details/gtveslqtrq.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtukvnyilj.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrujpjstb.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gtpgltafmf.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtuybjfblw.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtwbtvuhyo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtxcmtfwvn.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtjyhhhshe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtablnfxwe.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gtdfzltitg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gtjtgtdvwn.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtkxqwurjc.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtzwhsdjkl.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gtxjjuklvr.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gthuheigvi.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtegpzuagz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gttcjqwatu.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtwdsozcue.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtjtugjyds.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtgxonpikc.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtaxdevovx.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtyhvvswii.html

val m = mapOf("a" to 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgybvloi.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtwpqyzjxw.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtazfoymoh.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gttnvmxyad.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljmbtzua.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtymbfcvol.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtnqcghymj.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtzloulymp.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtdfkwlmqa.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtbmysmmso.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtubidxgiu.html


<!-- 参考信息 -->