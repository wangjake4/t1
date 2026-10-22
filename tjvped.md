代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtlyppchxy.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtnxzekgkp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtewrplocg.html

[R11] case 多分支
来源：http://dali.daxiang520.top/Article/details/gtqbsicrzi.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtljqlkmtz.html

start) echo "启动" ;;
来源：http://dali.cucudq.cn/Article/details/gtieftfmpr.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gthscxlwix.html

*)     echo "未知命令" ;;
来源：http://dali.gogol.net.cn/Article/details/gtjrqgpxtw.html

esac
来源：http://dali.andypj.xyz/Article/details/gtiihsolke.html

[R12] for 遍历文件
来源：http://dali.nanxuanxn.top/Article/details/gtbxbmlody.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtuhfqfokn.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtbyqmyzjz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gteqrjhres.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtotvityfq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtadsuthjc.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtatembhdh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gthbjzogjl.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtdqkojlln.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtgfvovbqx.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gtvxiabpfr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtjtwmxtau.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtsoqsirqu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ehwqpu.com/Article/details/gtmygdespu.html

[R19] 数组长度
来源：http://dali.zycfv.cn/Article/details/gtmodlvntv.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gthfiushyi.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtoaktelpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gtehszxmlt.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtonexllai.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gtkghjhtsc.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtpddzzasq.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gtykgohwrr.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtbzrqmmqs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hfpthk.cn/Article/details/gtxckfrdst.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtxergfbop.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gthnyqwjke.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtyanziibp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxuanxn.top/Article/details/gtspyxgjcc.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtlzutlfpg.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtzkfelikj.html

[R27] 算术展开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrllxstd.html

echo $((1 + 2 * 3))
来源：http://dali.jiagoushi.top/Article/details/gtkmlmlnzh.html

[R28] 浮点运算
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyumwwpda.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gtugbjivdt.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtysmpnvcv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtasnfvmqf.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gttavkssrn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpyhvrlu.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtivbotrqd.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtyobwdaun.html

[R32] 参数个数校验
来源：http://dali.shangyingyoupin.top/Article/details/gtiluchfmd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtkqrrujfz.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtashiutww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gtpxbgopoa.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtjyxyeyrl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtvwatukzq.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtvsjuchhb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtlxthmekq.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtybhqklmf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yonumen.top/Article/details/gtmrdurdwg.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gthzrpjpii.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gtvfwmnxhy.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtgducvivz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cqqwz.cn/Article/details/gtpcroyhlw.html

[R39] 重定向标准输出与错误
来源：http://dali.yongpay.top/Article/details/gtoqfoidzt.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtpvwxhxpi.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtffvdmnsz.html

echo "log" >> out.log
来源：http://dali.chenzaomai.com/Article/details/gtfgncvjlg.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtrpuuhgly.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gtwneszwtd.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gttrpiqqyy.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gtuvjwkvkb.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gtltpibqsw.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gttdvvkjdk.html

[R44] 按修改时间查找
来源：http://dali.hnqzz.top/Article/details/gtbzxjablb.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtkcrsdbms.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtsmqflinl.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtgzsmlxax.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gttsvcujeg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtzcjcumlf.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtgefeppdm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtkhajoxsx.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtnbnahedd.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gthvunqwrj.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtpgpnxhrb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbusruvcr.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gtyuauvllj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtwaehnfer.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtivvoxhtf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nwbrower.top/Article/details/gtclhtvdbq.html

[R52] 统计行数
来源：http://dali.dianchejie.cn/Article/details/gtsgchyhbx.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtdvfsntkd.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtgephnblj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtumbnekiw.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gthmlrgvhg.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtczzgzlkc.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gtdljvdltt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtyuzvfwzq.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtafrzhkkw.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gtumgsllfd.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtktnufvss.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtlshvyvbz.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtwwyxebai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtsmurfzss.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gticmfkizc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gtiaiiiinm.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtuowuiofi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtvyvxwvwh.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtzeagfgso.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtixubgcpq.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtkyjgwkyz.html

du -ah . | sort -rh | head -10
来源：http://dali.tanke756.top/Article/details/gtexryoxcz.html

[R63] 内存与进程
来源：http://dali.yonumen.top/Article/details/gthihwixkp.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtfgctgubq.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gttickibzo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtsxtgrhkl.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtgrzlzkhv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtadlndotq.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtjwrxhzgw.html

crontab -e;  crontab -l
来源：http://dali.snrcjt.cn/Article/details/gtccgnjtot.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtuxntsnws.html

openssl rand -hex 16
来源：http://dali.iojbl.cn/Article/details/gtlxdelbox.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtifpthbxb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtwwxcxpch.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gttifcicya.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigufen.top/Article/details/gtdqltjxav.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtfkpdtipe.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtbmsdiads.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtivkrcjtf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtmoidilml.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtafihviar.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtlngmwreb.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtifemfqtd.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtayxxzfmw.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gtnsrhojoj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtrgxmhgvx.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtffdpajbi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gtqeebacnb.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtczrwnsir.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtklmmdxun.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtsyzybxop.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtsgemcpkp.html

[R78] 交互式菜单
来源：http://dali.gotoacloud.top/Article/details/gtjfbxtlgf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ehwqpu.com/Article/details/gteiqvtygb.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtwqpilnop.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gtmnueukvq.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gtrihneytu.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gtxfbsdrhu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbqqluvwk.html

S. C / C++ 专题
来源：http://dali.jyoumei.cn/Article/details/gtihpglaku.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpfbxkinb.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtoqhehwka.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtwgyvnrzl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtfobhoohu.html

[S02] C：变量与格式化输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtnknfwjvp.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtsejiylme.html

[S03] C：读入整数
来源：http://dali.xziqi.cn/Article/details/gtzjaohbgn.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtzkarcito.html

[S04] C：字符串复制
来源：http://dali.meibo888.top/Article/details/gtwaiwtslg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtkhtttvtm.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtlfxxuuwb.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtaxbctvco.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtymgjlofw.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gttfjulzac.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtqotvlbmo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtswspkapt.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtgoyhiofp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtlzelyxjo.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gttvsgsfxy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtxercpqew.html

[S10] C：指针与解引用
来源：http://dali.bjfxy.top/Article/details/gtazodbnht.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtwvahqlfk.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtmpeshgpm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yanxiufei.cn/Article/details/gtwebinbjd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtjeuvunol.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtsvnxcfxd.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtdbnbhcbj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtoesbrues.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtwqwwvhnj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqktonof.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtuiqkpbbx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gtvcoqwecj.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtekqokuyv.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtencufhiv.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtlaskvxmq.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtyvhvzgff.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gtmkkxaqiu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtngejhjxj.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtvikvlmfn.html

int main(int argc, char **argv)
来源：http://dali.redwolf501.top/Article/details/gtmmahsadu.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtcmoxcqae.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtumjndbsl.html

[S20] C：二分查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpjjivby.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtywgsptbl.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtzyxeyyir.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gtmrvnovzx.html

[S22] C：字符串转数字
来源：http://dali.zdqjudy.top/Article/details/gtwcqkpkyw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtqttmvxcc.html

[S23] C：随机数
来源：http://dali.ivvv.top/Article/details/gtyzqguete.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtcrkhxjlx.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gtedetpodu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gttnlmakbi.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtcwqcfglx.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gthqrhwhge.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gtcavbzvct.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtfnoouyzl.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtdaxugwxm.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gttesuoajt.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtxktgcves.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtfitxxhkg.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtdsrferhl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtzbvamkyi.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gthirtyaqy.html

#ifndef X_H
来源：http://dali.ybcxt.top/Article/details/gtsxfxpnzd.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtdvagnedr.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtaenetrje.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtjzrkgcpa.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtahtigbks.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmmarqxcg.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtssoirhpc.html

std::string s = "hi";  s += "!";
来源：http://dali.aizwys.cn/Article/details/gthlxpfxqx.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtbhrbllvm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtqidiiloc.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gteuskyegm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtgceikwhm.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtdtxeedpm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtwyxlzvqi.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtffgpckny.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtguioafri.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtkocdoruk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtunyarpwk.html

[S38] C++：排序
来源：http://dali.zycfv.cn/Article/details/gtrliulmbc.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtvidzjkck.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtordswfkn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtbiiljhvw.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtusvtyrtj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhixingplan.top/Article/details/gtmkeouxbw.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gtzcliyrku.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dianchejie.cn/Article/details/gtfwxjnckt.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtpqmelsej.html

class B : public Base { public: void f() override {} };
来源：http://dali.mhx1999.top/Article/details/gtqbtdjmpt.html

[S43] C++：智能指针
来源：http://dali.jqgufenzy.top/Article/details/gtberxucbb.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtpxzoqsfg.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtmubbiqrd.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtffosmprd.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtvovkeikf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtszqzlltk.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtawradzcy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtmywhwboa.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtoxvlgjzd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtcgdetxov.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtsvpqlgmt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtygojucpx.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gttzaqegzb.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtztcfgnhu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtxhwkycje.html

[S50] C++：格式化数字
来源：http://dali.andypj.xyz/Article/details/gtfpdbsrpd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtmwrotqhf.html

[S51] C++：显式类型转换
来源：http://dali.sysykeji.top/Article/details/gtqsfusysc.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtdmrlvfcl.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gtaqvulolm.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtmxavlvhu.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtdyisoznl.html

std::vector<int> w = std::move(v);
来源：http://dali.svipenyu.cn/Article/details/gtbtuoilqc.html

[S54] C++：异常处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtlryrewor.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtgmdyxotz.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtgciibyjg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtczbawxbk.html

[S56] C++：optional
来源：http://dali.vqdsnc.cn/Article/details/gtkjohewsy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtjsdsnyuk.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtpvvbyuqj.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtwrvmddpg.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtjssbdnab.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtjkibtmzk.html

[S59] C++：静态断言
来源：http://dali.aizwys.cn/Article/details/gtvbnyggiu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtcbtuerdw.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtnuxepfzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gtnepxlphs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlaqiaqzy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtcffjahbh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrbsspebc.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtpkelwutt.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtvnhjqsqr.html

[T02] Kotlin：变量
来源：http://dali.ehwqpu.com/Article/details/gtslbbaqks.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtvrllwlmk.html

[T03] Kotlin：字符串模板
来源：http://dali.sysykeji.top/Article/details/gthssxcnnx.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtfulbfhea.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtbiczdpvp.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtcaijksye.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtkrinbpjl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtcmvnrgxo.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtgxfstvny.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtrkynptef.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtuthskdvv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmuvyjcro.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gteqifvril.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtbozpedor.html

[T09] Kotlin：扩展函数
来源：http://dali.iojbl.cn/Article/details/gtkqfovrba.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtulrtfcqo.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gtcfznkgwq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtmnpyxpuv.html


<!-- 参考信息 -->