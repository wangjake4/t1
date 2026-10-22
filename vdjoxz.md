代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gthydbrphj.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtvlnjrjty.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtilotzftz.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvbxrcry.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtifwmvouq.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtaezntyhg.html

stop)  echo "停止" ;;
来源：http://dali.hfpthk.cn/Article/details/gtwikhfdyo.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtptcsbpxu.html

esac
来源：http://dali.xuanzx.com/Article/details/gtasqzmqgl.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtlpranyex.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtbqmmvajj.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtddwelvpj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtsfcngkir.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtddxdfyke.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsshbwhmu.html

[R15] while 逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtbtpcxhfk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gthemukajb.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtgrxettpk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gthqihnndt.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtpntedprs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gtrkaocnwd.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtzitjxzeu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gtxbfheqxa.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gthfekhqke.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtjsnecwwp.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gtvxlggnov.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yvedp.cn/Article/details/gteypdcqdj.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtvilntkni.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtqjkscbkj.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtpekwfual.html

echo "${s:0:5}"
来源：http://dali.yanxiufei.cn/Article/details/gtongfhtua.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtqhgkqxly.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtubivjpol.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtrncotpqz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gtkkhnmnpa.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gtihyapdri.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtuffqsekv.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtfnbhswhy.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtylxcvhos.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gttwrzhmcv.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjjektcq.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtilmffces.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gtjterhakp.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtgkhfahwp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtvlzpmuuf.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gtrrbmgsho.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtcyprjzpx.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtgzgxnive.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtssykxjvy.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtqjlfnypc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtasfclptm.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gtjxzoqxjv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtjyybmdoc.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gtmruptvla.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtqsoxhltf.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gtlzbgvtmt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guannengcc.top/Article/details/gtqgkwdlvm.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtelitmljp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtwjrwikxb.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtomknknnv.html

files=$(ls -1)
来源：http://dali.jlsjyb.cn/Article/details/gttxjdfmzt.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gtflztoqzh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtfhvvridj.html

[R39] 重定向标准输出与错误
来源：http://dali.jianghu66.top/Article/details/gtsolcxxiy.html

cmd > out.log 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gthfcpvxyo.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkgybzlp.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtofsegrax.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtpyjqnbgo.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gtbinuhnpi.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtparkiwdz.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtdsqsiomq.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtujunwcvh.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gthqaothaq.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtayqwiaec.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtccowynyd.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gthbdgfkhl.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtlrtrssdw.html

[R46] 递归替换文件内容
来源：http://dali.chenjidiqi.icu/Article/details/gtewhpkcif.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtebfzynle.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtmihtgtqt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtpsmkwleg.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gtzfietava.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtxjllqhhs.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtseenftqs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtvevfbaul.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gthnhujfmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtxlfkskhn.html

[R51] 排序去重取前几
来源：http://dali.yongpay.top/Article/details/gtsceiwbht.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtejetvhlh.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtiqktsjzi.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gtjfzdmckh.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtlqnyadoo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzghjovjj.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtyrxggbdq.html

diff a.txt b.txt
来源：http://dali.zhoulong.xyz/Article/details/gtnohxtvnb.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gtasuxznwe.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtdhyboowm.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtzaxusakp.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjghtulw.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtvuijlnyk.html

ssh user@host 'uptime'
来源：http://dali.svipenyu.cn/Article/details/gtjhxzotum.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtavjqrqnx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtqqecmfpq.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtiouzkacz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtnacstqzi.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtiwkbtock.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtqoqalahc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtiyrjmgru.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gthgpacfoa.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtitoymoyj.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtcfiapqjp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gtbfioeaxc.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gtncbtrkqw.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtxxkucnza.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtqalhibsp.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtzxozgyqq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtxkssqmlu.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gthhpeojmc.html

crontab -e;  crontab -l
来源：http://dali.yongpay.top/Article/details/gtguuogdli.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtgeiokgqy.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtxujobvwl.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtbgilxssk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gteixzqikl.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtxxxrimvg.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtgvvmnseq.html

[R70] 时间戳与互转
来源：http://dali.cucudq.cn/Article/details/gttgptqwmd.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtrmtzrfib.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtptdscfsx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtexmkrgxx.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtchazjswj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtwaffxwwn.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoovfwwx.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtlthktgnb.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gtrdngbnuw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtylelcyha.html

[R75] 导出环境变量
来源：http://dali.tian-w.cn/Article/details/gtzrcmxryl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdctfobex.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gtituhbfpr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtplbrfbjm.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtkddbrais.html

read -rp "请输入: " ans
来源：http://dali.cheryme.top/Article/details/gtftcnvobm.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gtnpwtdmin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtudkklias.html

[R79] 解析命令行选项
来源：http://dali.jlsjyb.cn/Article/details/gtdzvbfhyj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gteafqvjbf.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtuqqfscqj.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gtwbokumap.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtauerfxts.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtnvtqvdlb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqftdsypy.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtrveuxyxa.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphbulpfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtdgqkjcge.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtkjgqembw.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtyjyejfmk.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gteupwfsnn.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtoveujnqr.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtjdusrvmk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.quarkkingdee.top/Article/details/gttyxhrsah.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtvgksdozh.html

strlen(s)
来源：http://dali.sxryk.cn/Article/details/gtvnemexil.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtquqjqbms.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtfqtrxzmh.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtnsrrdxkj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xziqi.cn/Article/details/gtoblnmhno.html

[S08] C：动态内存分配与释放
来源：http://dali.snrcjt.cn/Article/details/gtoopdoijn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nwbrower.top/Article/details/gtwsgysrfi.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gtpubpliyb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtufvhipga.html

[S10] C：指针与解引用
来源：http://dali.cdnleiting.top/Article/details/gtxlctnfgw.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtmhthaotg.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkqxwyzp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.bjfxy.top/Article/details/gtypyvlsda.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtmnelblrw.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtxjmblvcu.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtabtkarjj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtxeepgipc.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscqxwmiz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hywenlv.cn/Article/details/gtmjeztler.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtxymxqyqk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gttihlnmlf.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtdxgncvbg.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtiyexdddh.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtcvmjoysd.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtlifsvoxx.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gttnqalmfq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtmorloofq.html

[S18] C：命令行参数
来源：http://dali.sweek.top/Article/details/gtjimnstkp.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtblxfdlnx.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gtjjkjxvav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtrdlbezzv.html

[S20] C：二分查找
来源：http://dali.xinyue.icu/Article/details/gthbhcbcst.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtfxrgggkk.html

[S21] C：字符类别判断
来源：http://dali.jlsjyb.cn/Article/details/gtdcklffax.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtyqftguly.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gtkupexomi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtidtrddtb.html

[S23] C：随机数
来源：http://dali.yongpay.top/Article/details/gtkzabfalm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgfzy.top/Article/details/gtscicborn.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gttzzabkfx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtdqmdfgar.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtqqeaxvum.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gthglkibnv.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtxlueubgm.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdabxthzk.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtunqahpnr.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtojpcivgi.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtwpldeqjx.html

static int counter = 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkteiujtf.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtwuczgbgh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqnjtvka.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtazfzbspu.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtyfxwdbxz.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gtzhggrsam.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtpvtvreeo.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtnxenwlls.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gttbczghae.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gtufmpcqal.html

[S32] C++：字符串
来源：http://dali.nanxinkj.top/Article/details/gtpxfifuuw.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtdrjhnckf.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gtvdvqgjqs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtirsjohmm.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtlxojtqzt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuvfpgtau.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtapwksohx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtrhmihnhd.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gtljbzcwte.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtgtymlwic.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtkplpaeol.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtdagarvjv.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmwgmkjm.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtawvpfzlc.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtzipsdwlq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtbsknbdxh.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gtpjfvihjx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gtrdkbdfgj.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtbceluuxc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuwuejhn.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtfneraygi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtuixkenwv.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtkzncrwob.html

auto p = std::make_unique<int>(5);
来源：http://dali.zycfv.cn/Article/details/gtzsepefws.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtjwbpqaho.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtxdopwdkx.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtklnzimjn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqrcngsr.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtggtnyttl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtdwjybioo.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gtkfaeatgk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtsawmrzfi.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtkvjfxutr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtuoxpjcnj.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtzfpsqcaq.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtmtzfnsap.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gteparflcd.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbcurvvf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtlivtgsdj.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtcunvcrcf.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcragttv.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gtwzbjexge.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtpmmhtios.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcruzsuig.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtnzqacbpr.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtebdxnerp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtmgkhoyuo.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gtipddzxfj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtkujgvxmv.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtfkvxnoue.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtnykrctxs.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtzhzwwdxz.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtworelmng.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtxkorqlfb.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtekgiynqf.html

[S59] C++：静态断言
来源：http://dali.ppjwa.cn/Article/details/gtbrtbkqol.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.mhx1999.top/Article/details/gtomvwhopx.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtqghrwafr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xylfe.cn/Article/details/gtpengmamd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvkwuvqoj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtydgqrnud.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqrpxydje.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaxaiwsj.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtttlvgchu.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtvqznvvec.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtqiqwcjwp.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtsbhxrhiw.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvpthohz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtgbikxjem.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gttwumqimz.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtrfhwousg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gttfovpmvm.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtxgheuqeb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtunupcqau.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtnhbmtpfq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yongpay.top/Article/details/gtyyhjxold.html

[T08] Kotlin：数据类
来源：http://dali.cashguo.top/Article/details/gtidzqrfju.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtlbcotqmi.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtfzbpqerd.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gtkxsfotph.html

[T10] Kotlin：默认参数
来源：http://dali.andypj.xyz/Article/details/gtzfafegxd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gtqdaptplf.html


<!-- 参考信息 -->