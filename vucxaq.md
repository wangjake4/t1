代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtfygnbdxe.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtwyapzubs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtofkwhseo.html

[R09] 字符串比较
来源：http://dali.316326.xyz/Article/details/gtcpfaxuhc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjeiommwv.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gtorxgejyv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtvzkhbzvb.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtsusbvutr.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofrioqki.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtwcxnskpv.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtlbcdqzka.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtphhercwd.html

esac
来源：http://dali.iojbl.cn/Article/details/gtygjlijml.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gthekhvbiq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtwpyuaydf.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gtkxoldapv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtudjiqsvy.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtvjxvgdul.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gthyqdpmgw.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtucwbrhgc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtigmdupsx.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtlwclniba.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtmyckioms.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtclneczmw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtfiifxhgl.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gtqtfvinlu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtwfjoguyo.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtmtrdmbyz.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gtmpzsmjbn.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gthvqazffu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtnxcbgnub.html

[R21] 字符串长度
来源：http://dali.cashguo.top/Article/details/gtxuvyijrb.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtlwbofotm.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtejojoilx.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gthvkcvrsl.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtukdasrpq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtperxsful.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gtdrmljfgv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.havefunace.top/Article/details/gtjehzffid.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtgexpsdqw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtnnpmszes.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtdynblosq.html

now=$(date +%F); echo "$now"
来源：http://dali.chenjidiqi.icu/Article/details/gtvmtnyejn.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtfpiotuqz.html

echo $((1 + 2 * 3))
来源：http://dali.nanxinkj.top/Article/details/gtmgoddlhi.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gtqegwvotm.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtmggcfonz.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtyamuxnpp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gtkgbsktjs.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtmnwoznmo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtatjgtfvl.html

[R31] 局部变量
来源：http://dali.hnqzz.top/Article/details/gtlfzpfouh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yangfankeji.com/Article/details/gtmonvsxaf.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtkoksutol.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtbdspegfi.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtvtgehvvh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shangyingyoupin.top/Article/details/gtbhtvpykd.html

[R34] 退出时清理
来源：http://dali.aibaodan.cn/Article/details/gtmgzxapdl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtkrhzewlc.html

[R35] 后台执行并等待
来源：http://dali.shzxlz.cn/Article/details/gtcflampun.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtmeifyyzf.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtssouwrec.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsfdzngu.html

[R37] 把输出赋给变量
来源：http://dali.c1oappe.top/Article/details/gtfiklqvte.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlcffrmyf.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtftndqqzb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtipkhgmry.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gtlmkkomel.html

cmd > out.log 2>&1
来源：http://dali.cashguo.top/Article/details/gthfhyupkl.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvofbsvvb.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gtexxnbzjr.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtewaipgte.html

cmd >/dev/null 2>&1
来源：http://dali.jianghu66.top/Article/details/gtjxtdglkz.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gttpvlkmal.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gttxzzlwdh.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gteghvifmv.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtpskpdfon.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtziitzvxv.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtjpxqoder.html

[R45] 批量删除
来源：http://dali.nanxuanxn.top/Article/details/gtxipcmend.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtqbgtkvpk.html

[R46] 递归替换文件内容
来源：http://dali.shuidangran.top/Article/details/gtgmcuuapm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtmuesoimd.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajzbmzeg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtylmlpiur.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtjevougay.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhbauiyp.html

[R49] awk 带条件
来源：http://dali.feifeiyinyue.top/Article/details/gtdwwfcdxs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtcenngpko.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtytvxraav.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtxqlgczor.html

[R51] 排序去重取前几
来源：http://dali.redwolf501.top/Article/details/gtjyafypsc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtbwwkkqzb.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtrvxemepa.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtigiumisa.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gttwjbagnc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtwfudvvru.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtpfctuuff.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtgzsnjbpm.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclmmaqt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtcqvhemlz.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtvpfdeiyb.html

scp file user@host:/path/
来源：http://dali.xylfe.cn/Article/details/gtxxrxyhux.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gtbtilqwxj.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyyyrnhi.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtfgkdgvpm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtgffztsfi.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtqbpixhzd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtmlmmdasn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtnilfkjsn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtqsgxuudb.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gthucswavt.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtsqktuzth.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtawahusfd.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtnqxeyesp.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtgonvigft.html

free -h;  ps aux | grep nginx
来源：http://dali.chenlongwang.top/Article/details/gtyffyeyuu.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtwbvbyxyz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtncwqixbk.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gttvdvstpi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtvgyocqcq.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtjbwqcclk.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtqxumfwbc.html

[R67] 生成随机十六进制串
来源：http://dali.sweek.top/Article/details/gtuaemzcsb.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtolkyclxj.html

[R68] 计算文件校验值
来源：http://dali.jqgufenzy.top/Article/details/gttrozhrew.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtoczzonov.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtbnlufccr.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnxiangtu.top/Article/details/gtlvymdajl.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtgoriiulf.html

date +%s;  date -d @1700000000
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvkbixbi.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gttgwlinpu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuanzhike.top/Article/details/gtdyacqhgy.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtyfvvzkfr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtzdeqacir.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtacgwmbaj.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtapodkgnl.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoukxwopw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtjcqallqv.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gtnwoiktxh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtdfrdgwgd.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtasqczsxu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtuqrhljmi.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtaugevhnf.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtynrpntej.html

[R78] 交互式菜单
来源：http://dali.yueranfly.top/Article/details/gtqdqjjnts.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhengqikj.top/Article/details/gtgcpxytsb.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtnhtvjeva.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gogol.net.cn/Article/details/gtgiumtrvh.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gtkeaecxhx.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtqofbziwi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtvniidpkc.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtjulztpsc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtafgclcia.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtrqnerahg.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtzaivcsph.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtyoiunnsv.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gthgylbyuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtpvpwwgne.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtpmwcahzo.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtykwwndsd.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gtmoicqkth.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdxpbojj.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtlbcrqklr.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtigsrbfxo.html

[S06] C：字符串比较
来源：http://dali.andypj.xyz/Article/details/gtobzedmzg.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtqwlghtmg.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gtdcskukfg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtqiclljoo.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtpczinmbl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gtqgzxhkco.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtbyiiqtxr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtxlrbxuxc.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtpqomnhin.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtglkvzpwj.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtbqvjsxyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtkumhigfz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtlowayoar.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtswlxyrdk.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gtmzvmqswq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtauaqmgrj.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtydqsqhdz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aizwys.cn/Article/details/gtmcmomrim.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtszhhmprk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtghihqanp.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtdkffsfxo.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtfmyzflft.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtzqkckuzk.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gtfbzqrysz.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtxngxnbfu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtabpwprrh.html

[S18] C：命令行参数
来源：http://dali.havefunace.top/Article/details/gtnxynedav.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtihhlozic.html

[S19] C：快速排序
来源：http://dali.shzxlz.cn/Article/details/gttigkozlx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtxzfwrkyr.html

[S20] C：二分查找
来源：http://dali.zdqjudy.top/Article/details/gtuarcrvfw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtahpubmwv.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnupebuv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.bjfxy.top/Article/details/gtlwtjvpwx.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtdodunowz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtpqltheya.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtovbkckpc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jiagoushi.top/Article/details/gtxnvnnlkw.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtfxlapwhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtdvbitakc.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtmnxebwfg.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtiavvpway.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtthfzkoak.html

memset(a, 0, sizeof a);
来源：http://dali.yj202588.top/Article/details/gtbeucvbcs.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbdzzhjg.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtmqhjacvc.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gtpzmdwgzo.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtsczwjend.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtgxktgtjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtmrtosjko.html

[S30] C：头文件保护
来源：http://dali.gotoacloud.top/Article/details/gtmksiyedl.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gttomgjxjm.html

#define X_H
来源：http://dali.birdmap.top/Article/details/gtocgpjrgn.html

#endif
来源：http://dali.ivvv.top/Article/details/gtmtjlpheu.html

[S31] C++：Hello World
来源：http://dali.yuxming.cn/Article/details/gtdjefmgag.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtctvsiess.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtlmrggqvu.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtjijnksdc.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gthjxvdtfa.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtbaxebrlf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gteirysvvc.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gtwqarpjhp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtakbtmiqk.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtczghhjcs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gttzvhckca.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtrsfexbls.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtkzuuvnon.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtbyrnyebg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtdwavjxsn.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gtbljdnjzb.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gttsdysuwy.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtpbmswjqp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtqdwnfbhf.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtehlqnpty.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtpjtrfdeh.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtnvgqglnr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtocxvonrx.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtjborzelj.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtiqryxufe.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gtfsjfhhtw.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtfjjchlli.html

[S44] C++：引用传参
来源：http://dali.guannengcc.top/Article/details/gtfhseglhc.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtihivqkgl.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtfntwzdsb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtkbbmydfx.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtqmzlckgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ybcxt.top/Article/details/gtgsehywrg.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gtdxadyqat.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtwdhqmwwo.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtgynkzwfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzlannwt.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjxngrqt.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtigbkcygi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gtfeahbinr.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtapkshhzj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtwrjlahcs.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtybunrcpk.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gtwgxdtyzc.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtsnkkvayq.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgscvvppz.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gtuedoywbc.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtjgjndxkk.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtwlxrpmqb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtlfykafcz.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtsvtxbxtf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258888.top/Article/details/gtcxsynoup.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtuxgzhplj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhengqikj.top/Article/details/gtjfyyynrs.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtyjauzwpx.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtcmvhglsb.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtsbspcvfq.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gtrrqmxegw.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtpqogvczd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtxbeojlgu.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtqcgwwtms.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtwgjxetra.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtviunnctt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtomllugur.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjqdwjrlu.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtvxvtkmwk.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtsvnrtawb.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gtbwqpddai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gthaayypjh.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtcealinjx.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtcohehyiu.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtbzhzwmnu.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtitztihic.html

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtieobnfxv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gtdqhutilu.html

[T06] Kotlin：集合映射
来源：http://dali.hnxiangtu.top/Article/details/gtcjwjucgw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtvdsnmakz.html

[T07] Kotlin：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gthdaknnnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtiwavmqdr.html

[T08] Kotlin：数据类
来源：http://dali.cheryme.top/Article/details/gtqxlpxagb.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gtwzplwqbq.html


<!-- 参考信息 -->