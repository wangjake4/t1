代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtpvhmoorf.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtjhvcenev.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nwbrower.top/Article/details/gtzzbnmtyx.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtodujklnm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtnmxtewgg.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtvsnjebat.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtpvwxvdfv.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtnuwuwwtm.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gtsidikext.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtaktlugbt.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtemeunlkz.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtqbvtkvtu.html

esac
来源：http://dali.xuanzx.com/Article/details/gtdcjetips.html

[R12] for 遍历文件
来源：http://dali.chenjidiqi.icu/Article/details/gthodbznwb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtvteizamm.html

[R13] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gtknvhhtdx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtgwfzkywn.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtjaecjsuv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtzxadtgcg.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtwinhxrmu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtrymkhdua.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtfwpwxniw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtscbrhpmz.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtwgukfemp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gtqstxkuii.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtpjqhljun.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtmtjteoyt.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtygjxosgb.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoibghupa.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtgnxbwexu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtudfobutd.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gtfzphmyiw.html

echo "${#s}"
来源：http://dali.cheryme.top/Article/details/gtrkspxcoi.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtdwphublw.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gtcztofadz.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtrddnmjpb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtqiczmfyg.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtbxkdvkap.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtlestpceb.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudulenma.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gtdyqyivtw.html

[R26] 命令替换
来源：http://dali.birdmap.top/Article/details/gtqtzxkhdd.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtdcfdrjgq.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtvyraidqc.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gthadnaiga.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtrwfkbqwh.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtrrfijcgc.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtvhplpayh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkopolcf.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtssmffgqh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtriecxffo.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtaqekrpvg.html

f() { local x=1; echo "$x"; }
来源：http://dali.svipenyu.cn/Article/details/gturiyiiys.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtnrsiuvrs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzaqksxcg.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtjjawipwl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gtmxeoffdj.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwcxzpfn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtkjzcrlay.html

[R35] 后台执行并等待
来源：http://dali.xziqi.cn/Article/details/gtdmrfgoyd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gtnrelhbik.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gtxvydleum.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcevntbp.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gttondyebc.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gtrxtmdubq.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtmtrazgud.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aizwys.cn/Article/details/gtuoixesty.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtkkrztvfb.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtfhsmlvcc.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gttbkvjpdz.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtrtqhlfch.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtwxjjbjba.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gtxeloxtjm.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtblviwjye.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtrfpobztn.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtfsdjwavq.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruqjfopv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtxvtoekku.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtxczmuhks.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtpeykthgn.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtdqhrpmsq.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gtmjjsqsfe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtkfyaarcl.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtcgraifbj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtwofvihqz.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gteftnrbsx.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gteielorji.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtgwqdykdf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtfemfryat.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gtsaorciif.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtfzbxmmof.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtbfyerrgy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtzzlcbyls.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtyrgmcqsd.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtajzlykhn.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtxxqqbtnq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtknjggaag.html

[R54] 比较两个文件
来源：http://dali.ivvv.top/Article/details/gtpkbagazq.html

diff a.txt b.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntczlzcx.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtluzvwswh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtlvffnutu.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtqwvjtvyo.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtvpzmuezx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gtecmrrxjp.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtjcbvdlae.html

[R58] 下载文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrqhcgqz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtmtwmdbup.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtoarmwsrx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtoflyudqg.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtrwspayvd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtzbvmifyn.html

[R61] 磁盘占用
来源：http://dali.havefunace.top/Article/details/gtylcfoltp.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gtnajqdgyl.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gttouzzlyx.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtmfutyalj.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gtztqgcdmf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtvsyiztdg.html

[R64] 结束进程
来源：http://dali.shzxlz.cn/Article/details/gtjerxyppa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yongpay.top/Article/details/gtzfdjmjas.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gtgdidqfwl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtrswwtikh.html

[R66] 定时任务
来源：http://dali.meibo888.top/Article/details/gtdnpiijgz.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtugwdmbvv.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtkuffyerw.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtecxkplgh.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehbzxdzh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtgsfsfefq.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gtjsegfijw.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtatpegnyk.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gtdpyyslgr.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtqseqxdxg.html

[R71] 日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtsvavimdc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtvolampss.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtygtlsxzq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gteyrxbazi.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gtviijcwiy.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtjzgvlzla.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtphgropod.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gtwaelbuik.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtovzqzhzt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtpsgjtubn.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtxzobtmnv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtcpdloipu.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtmfnufpzi.html

read -rp "请输入: " ans
来源：http://dali.havefunace.top/Article/details/gtwkhxyzbe.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqopscom.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xinyue.icu/Article/details/gtykmukhpq.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtoatkmsdi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtdjbocohg.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigfzy.top/Article/details/gtvnnylcgk.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtolyunzwj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfewlziga.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtumkrjlsl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtafopbqjq.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gtlfrczfph.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtvzgjvwsj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.kuanghao11.cn/Article/details/gthoiiiqoq.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gtieoykbrl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zdqjudy.top/Article/details/gtbtqttwyd.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtsbaimiug.html

int x; scanf("%d", &x);
来源：http://dali.0kj1m.cn/Article/details/gtolahitov.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtymfwlqdx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guowangkeji.top/Article/details/gtbjkrseet.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtlzfoolpn.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtpuabfakv.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gtjkkheqgy.html

strcmp(a, b) == 0
来源：http://dali.haohaochexian.top/Article/details/gtqcoydbuy.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtdadrweld.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cheryme.top/Article/details/gtalhygnoq.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtorqwlqtw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gttuqgucfk.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gthpzhdyjl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtvdyyogtk.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhttlnrt.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbxozunq.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtgljcoamp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtrvqjeiof.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtiimrplhr.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtzenjsrux.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtzdwaofie.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtokxyvqbj.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtvdkiuutm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtpnxoefuy.html

[S14] C：枚举
来源：http://dali.bjfxy.top/Article/details/gtkxbqseqy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgufenzy.top/Article/details/gtqnnjyyoe.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtjpcxpklf.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gtmuagwnzk.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtsulwkxam.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtblmedxwi.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtydvgcbti.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtplrcujqz.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtfhzwarcg.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtlyrdjxvd.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryzpkepm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtmztoxkwz.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtxrwgjlyg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtgqtxiorp.html

[S21] C：字符类别判断
来源：http://dali.c1oappe.top/Article/details/gtngmkkhmn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtrvvsmqrg.html

[S22] C：字符串转数字
来源：http://dali.hfpthk.cn/Article/details/gtacvvkrom.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtbutuoncv.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtsqadpxdl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtlodehsgp.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtyoiimlnu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtwtnjvugz.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtaokqblug.html

memcpy(dst, src, n);
来源：http://dali.vqdsnc.cn/Article/details/gthbfaralc.html

[S26] C：内存清零
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmeardmc.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhuuxhjg.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtutfqvibi.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtpwfxytkj.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gttzcodfjh.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtnrjodanr.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtdzmwhlzc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtbryfybns.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtyagwwkni.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtdcznkwtr.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gthkvfrixz.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmebnfpr.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtqubchsjc.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtmagocoyj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hysaishi.cn/Article/details/gtrcwbigrd.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtijihjvin.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtzziofiex.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtkwtpwsyw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yongpay.top/Article/details/gtbycznawq.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtncrjgsjw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hongshengwenyu.top/Article/details/gttjwacchf.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjqyutwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtacaujhja.html

[S36] C++：unordered_map
来源：http://dali.gotoacloud.top/Article/details/gtbfxahyxh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtidytvqvu.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gtxlsentjd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtcwedmtzs.html

[S38] C++：排序
来源：http://dali.daxiang520.top/Article/details/gtbvcxplom.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtkakgqxrk.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtvlqdnpvf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtshznbalt.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtmcjmpifu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gtbfdrtvno.html

[S41] C++：类与构造函数
来源：http://dali.yueranfly.top/Article/details/gtngaquswc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gthqehnitl.html

[S42] C++：继承与虚函数
来源：http://dali.meibo888.top/Article/details/gtzlqxsohk.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtdtiihhar.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtpjipdsgd.html

auto p = std::make_unique<int>(5);
来源：http://dali.ppjwa.cn/Article/details/gtyueuloqk.html

[S44] C++：引用传参
来源：http://dali.ybcxt.top/Article/details/gtqbgxohwo.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gtqqqwpdmb.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbxawuyc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkehpwjd.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtvmtldgov.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtwalcmari.html

[S47] C++：结构化绑定遍历
来源：http://dali.gzhubu.top/Article/details/gtetotjrqp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtrunyirwt.html

[S48] C++：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtmwednixn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtjbxwhfbd.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtrgehlagw.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtsvfeswax.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtreuclhgh.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtgnpiageg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtvffkkufe.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtfrjkmwqx.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtzrsdrimd.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtnhuwqwpd.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtyrlywaop.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gtkabpnrkx.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtvmddsxfb.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtzwlafbyp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtegijpqfu.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtvnpvcioy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtoqmqgfmb.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gtzsggqdto.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gthcncoyju.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtgtbphdrh.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtessacxvx.html

[S58] C++：命名空间
来源：http://dali.ppjwa.cn/Article/details/gtzqttyoff.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtgaburvda.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknajzfnr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtljkthkte.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtickucwjl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuxming.cn/Article/details/gttkumugde.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwynhgevx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtvetkrvxj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttclfhejf.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtammwnmst.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxijjpwoe.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtfofidrbb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtrblrbaid.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtkviifhrt.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtcjnjceec.html

[T04] Kotlin：空安全
来源：http://dali.meibo888.top/Article/details/gtzxzlhjda.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtlseegncr.html

[T05] Kotlin：when 表达式
来源：http://dali.dashuyun.cn/Article/details/gtzhigducm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtglgqxbks.html

[T06] Kotlin：集合映射
来源：http://dali.daxiang520.top/Article/details/gtgkmbrueq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtlbixqdbz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtnfxhmmhv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gteeytjjql.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtjlenfgik.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtxjgzsrec.html


<!-- 参考信息 -->