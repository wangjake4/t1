代发 wailian999

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gtxdqcmfve.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gthgwinmes.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtoruamerh.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtuqliysck.html

esac
来源：http://dali.dianchejie.cn/Article/details/gtmeiovumb.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtlfcqlqwc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtdhhincwh.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtseoywtlx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtjntsyvga.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzelyffk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtvwqvvrnn.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtqltoqrmd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.mhx1999.top/Article/details/gtnttptfih.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gttjayimxd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtrwsztxtm.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtzofpsenv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtuyrwzkot.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtchxgnlfa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gtjofqldwc.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtwcnrrfuw.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gtbminvdix.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gtzmmpvjey.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.dashuyun.cn/Article/details/gtygbsapav.html

[R21] 字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtprhjdqrw.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtbwxtshhq.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtzdfxbgzr.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtmrcnlwig.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtyqxhbkgc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtqtzueqoe.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtuukxnwse.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtcugjkovg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gtfrxguwxj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtguzawtjt.html

[R26] 命令替换
来源：http://dali.yj202588.top/Article/details/gtkmcowgqf.html

now=$(date +%F); echo "$now"
来源：http://dali.gzhubu.top/Article/details/gteqwxjsqe.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtcvjssbsf.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtyojzjnkw.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtkgijoezj.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtlozsrbtp.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtwqcxeocc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuanzhike.top/Article/details/gtvkuejtgb.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtxluvjhbj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtaojhpcoi.html

[R31] 局部变量
来源：http://dali.yuanzhike.top/Article/details/gtubroxvqr.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gttgiapudn.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtzrvrbsbb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtffrnocoh.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtjhrlnsgd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangshuangyany.cn/Article/details/gtcefhniyh.html

[R34] 退出时清理
来源：http://dali.shangyingyoupin.top/Article/details/gtjcafadjd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtjrysiwqb.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtmtnyvjqh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtiygiymdr.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtieuoieyv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gtfbobmkns.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtntssikxh.html

files=$(ls -1)
来源：http://dali.smart0.xyz/Article/details/gtaoombjxc.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtpmlsutmm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gtanhvmggo.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gtrgedmpey.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtsnfapack.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrqtyepx.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtjigcmucf.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtybdkemmb.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtumvmmonz.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtzghmnybh.html

wc -l < a.txt
来源：http://dali.zhoulong.xyz/Article/details/gteebichad.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtzsifxvyl.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gttlussncp.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtvtiaudwk.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtldweahlb.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjliptei.html

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtbhdgvpms.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtzlmbqdec.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtbxjthozw.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtuywirjsh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtptwuyhbm.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtdzsakpvz.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtsbtegrwn.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtisfmmbmk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtiolltgps.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtyplgupfh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtsbjhpttt.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtxvdtwekf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtrwzfggct.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtjpgsqvqh.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gtvsjlgprj.html

[R53] 查看文件头与实时尾
来源：http://dali.wangshuangyany.cn/Article/details/gtltutldfg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtnfpccwfc.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtbgcdzsvb.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gtdwlgpsqa.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gtrgxwvfsh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtituemcjl.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtkmukshne.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtozsoztww.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtcbaalptm.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gttrwsrdty.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtlwnctsjd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtiamzoksg.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gttxjgtqir.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gtfgjytasr.html

[R60] 只看 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtjkjefmco.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gtdrbvjerr.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gtrzoalaje.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtizulmfaf.html

[R62] 找最占空间的文件
来源：http://dali.yuxming.cn/Article/details/gtngjkjkih.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhrqqmtc.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtvfjzqfyg.html

free -h;  ps aux | grep nginx
来源：http://dali.yj202588.top/Article/details/gtjdxptgfo.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtlcsqhrqh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtwyuqqctd.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtuuhobmdt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gtqnukrivq.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtrbtbttyw.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtmjvbcyhi.html

[R67] 生成随机十六进制串
来源：http://dali.zhiwuduotai.top/Article/details/gtydronxda.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtvfaxdcrw.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtrnujtpnq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjozwmdcb.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtjtqyusch.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtvzfypwfm.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gttdctsodz.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gtbxisstyc.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtztuiebqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtegeefnlc.html

[R72] 等待端口就绪
来源：http://dali.jyoumei.cn/Article/details/gtkzksjrec.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtzztfzfhm.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtwjbnxurk.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtrvtzudgx.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtzrlabtsc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtjcoblejf.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gtanhjyxqj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtvmsafkfx.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtidslhrhv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtyswurhhu.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtkricfijx.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhwrksoh.html

[R78] 交互式菜单
来源：http://dali.ivvv.top/Article/details/gttebwtdmo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtiyxplhld.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtllbifeof.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gtacbbsuga.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtgpxtlhhh.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gtjmhldwkk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtalgkjyyt.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtvqofdial.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtzaomffyy.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtvvllvrrw.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtfxjljagw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gtnixdtgwc.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtnqnqrbto.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtsdcikaoo.html

[S03] C：读入整数
来源：http://dali.gogol.net.cn/Article/details/gtvqkoftrs.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gthhzhjhit.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterimoeuv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtjrtfysnu.html

[S05] C：字符串长度
来源：http://dali.aizwys.cn/Article/details/gttgwmxoxm.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtuocobfzo.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtpipsjacx.html

strcmp(a, b) == 0
来源：http://dali.shuidangran.top/Article/details/gtvxlteqsx.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gtqvzytbfg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtnzbbtycr.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gtlcahsgql.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gtoaucqrom.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gttzshspjg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtiudtykix.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtmeblkvbi.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetdiphus.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsbvqanpf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.feifeiyinyue.top/Article/details/gtkugmfbec.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtghaowabp.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtjhzeklyn.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gthnzrmeog.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtrfhojjxy.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gtakuioevc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtfntvzrfv.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtazfmfzao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtmbhtobwy.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gthzsgcmjj.html

(double) a / b
来源：http://dali.zhoulong.xyz/Article/details/gtuncrmfyz.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gtakminwxs.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gttroyfryw.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gtgftewhau.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nwbrower.top/Article/details/gtnouvbelf.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtcitthfzq.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gttmxbtuhj.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtultforun.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gttmfzlftk.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtaaiqyseu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkvoqcpx.html

[S21] C：字符类别判断
来源：http://dali.sxryk.cn/Article/details/gtplzjwtje.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.andypj.xyz/Article/details/gtmimadfty.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtwjqviarl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtxkpkxppm.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtigachivl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtsvimzudo.html

[S24] C：获取本地时间
来源：http://dali.sweek.top/Article/details/gtihbnuvsg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtbqdwhtmm.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtgfogrpov.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtosxatiei.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtpcqqxdvd.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtubxaprwb.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgvexhnx.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtbrnlpcjg.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtqhiyqyyj.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtgxvyichi.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtzwomrhho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xylfe.cn/Article/details/gtbbfobtoo.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gttylsvtms.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtvqvnupwl.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtqidbreja.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtodklpwdi.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtoqjqbtbp.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtyqctlbbe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtwynpgamy.html

[S32] C++：字符串
来源：http://dali.cashguo.top/Article/details/gtizniikef.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtteugddzg.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtlonndrga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtpbflwpsr.html

[S34] C++：遍历 vector
来源：http://dali.shzxlz.cn/Article/details/gtsieqoosl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gterwrkion.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gthyvocxra.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtvrzxaidw.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtnxjakman.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtzktodatc.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtmkihdfpr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtwdwuyovj.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtonoqdznl.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtsswvofcp.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtqrkavjtv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiyznrqz.html

[S40] C++：查找元素
来源：http://dali.xinyue.icu/Article/details/gtjrjyoedc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtrrzcdimx.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gtwkhvvetk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtzdfrttqf.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtiqowrkis.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtoakoonjh.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtsfzagtcb.html

auto p = std::make_unique<int>(5);
来源：http://dali.ivvv.top/Article/details/gtgxnehvei.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtvknemyxs.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtltkyviio.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gthkaqzwhz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtkbxyqvsw.html

[S46] C++：函数模板
来源：http://dali.tanke756.top/Article/details/gtsqhgfway.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtbvwgyewv.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnsqomdk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtwtraxbqv.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtlshkngib.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtbzrmdehb.html

while (std::getline(in, line)) { }
来源：http://dali.xuanzx.com/Article/details/gtixusruby.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtnaixddjz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gttobejvxn.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtctzexdab.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtymxfnzap.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gtpeapdgwa.html

static_cast<double>(a) / b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldtjvpro.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtuchfliin.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gttkoeyfik.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtspzfxdep.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtwdoxcdev.html

[S54] C++：异常处理
来源：http://dali.pycfn.com/Article/details/gtzfhpzfxs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gtvvskbjic.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtlkmlhjkc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtgitapkna.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtirfeitda.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gtiqjisljv.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtxnjthkkb.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtcrnilvhu.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gthfoxsqkj.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtmroemjho.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtbkmxxzij.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtftyephel.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtgatculpq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gteotokkav.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjlxjknul.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtrkkjeiqh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpnqdltvy.html

[T01] Kotlin：Hello World
来源：http://dali.cheryme.top/Article/details/gtwmvyiotc.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtemjjsdgt.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfxvfxmq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtvquqqmki.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtxlkdjdtk.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtxcrvraoq.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gtnxptlxqn.html

val n: String? = null;  n?.length
来源：http://dali.jinqigufen.top/Article/details/gttwxyclzd.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtbsxjepet.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.bjfxy.top/Article/details/gtyoxrfdvc.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtwrnmimhp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gtjhtqwuju.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gttirzbjnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtehajqhtn.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtxylxdofs.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtfmqligpb.html

[T09] Kotlin：扩展函数
来源：http://dali.dianchejie.cn/Article/details/gtccbpptmg.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtaaktdiaa.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyollgfg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtkqxkrlmj.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtuohoakzp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gtckmzcgex.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtezrphuyx.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtwhbvyutn.html


<!-- 参考信息 -->