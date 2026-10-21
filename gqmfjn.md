代发 wailian999

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtyxvwwvca.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqndebsh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtnnencrwd.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtlxlqucqr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtianzadyb.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gtfmbwsioe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtfpdtnltz.html

[R09] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtjrjipoim.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtsxyvgqtb.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtpoevmoxp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtixiavctq.html

[R11] case 多分支
来源：http://dali.hnxiangtu.top/Article/details/gtgbeuejot.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtsgvrtiqi.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gtvlyhhzgu.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtzaggdfem.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtywkcewgn.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtbsrkuhml.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtazizgily.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gtmwpvoqgn.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtwqyhlyvm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtildrckmj.html

[R14] C 风格 for
来源：http://dali.cdnleiting.top/Article/details/gttjjgugud.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtizgkygsg.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtbhvzjlmr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtbygbtpio.html

[R16] until 等待条件
来源：http://dali.yangfankeji.com/Article/details/gtawgzbdqn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtkvphwnhc.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gtuvhaldun.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtmiswkqfs.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtfqqyoyar.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtxhnmomla.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtrheaankf.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtuvicdcio.html

[R20] 关联数组（字典）
来源：http://dali.guowangkeji.top/Article/details/gtgifsqntm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtsvoftsqv.html

[R21] 字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtzpthhfqp.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtiwdfdwms.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtmqgedsht.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtwzossbmo.html

[R23] 字符串替换
来源：http://dali.fengsongda.top/Article/details/gtmkiuvrfb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtrsjpkfdy.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtbgorrrra.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cdnleiting.top/Article/details/gtxablvruv.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gthrtxaspk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtcauzfgdc.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtghbwxbtr.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gthufvepgn.html

[R27] 算术展开
来源：http://dali.ppjwa.cn/Article/details/gtphbcbafm.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtpbqkwzlk.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gtorkqxzjb.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenjidiqi.icu/Article/details/gtyxcvvuyr.html

[R29] 定义函数
来源：http://dali.daria6918.cn/Article/details/gthsyubaip.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtvvthocmp.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtgwntbnwf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtpaxblwap.html

[R31] 局部变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhswcdjv.html

f() { local x=1; echo "$x"; }
来源：http://dali.xziqi.cn/Article/details/gtumfsnfus.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gthlcnubde.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gttfncmwwl.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtjvnpfzki.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hfpthk.cn/Article/details/gtjwtyyfjb.html

[R34] 退出时清理
来源：http://dali.pengpengdd.cyou/Article/details/gtesjeqyma.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtyaajrbbm.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtvfgbaqeg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtglvwjaxj.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gtqabvpeyr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtgatizmmh.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtmjnexfwu.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtfrhdvvkk.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gthnyykpbs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gtdugmismq.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gtgvcitwmd.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gttabxexoa.html

[R40] 追加写日志
来源：http://dali.ydzc1.top/Article/details/gtrswqjemi.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gthbtlzybf.html

[R41] 丢弃输出
来源：http://dali.sweek.top/Article/details/gtsxujvknt.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtvpefnlix.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtkizdzdfc.html

wc -l < a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtfowmuhxo.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtkqkdjxhb.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtuqondklm.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtxiuiuzen.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtsmuuiwzz.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtitwsmuyx.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtyccmzucl.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtylpcdeve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hongshengwenyu.top/Article/details/gtzvqiltre.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtvljpyalb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdegczsog.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtvfdwfxgl.html

awk '{print $1, $3}' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gteakznqqy.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtgsykwuks.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258888.top/Article/details/gtpifvvosl.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtugmreivy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtzoirnvwa.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtreigqtlj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtewaewfey.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtamucwavu.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxlwogho.html

[R53] 查看文件头与实时尾
来源：http://dali.dashuyun.cn/Article/details/gtfaalbxcg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gtswpglxzu.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtzsinypay.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtnitgvolk.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gthqpupmsk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtzmhqmnqn.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtffgiyepu.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtdzckpdad.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtfkdypssq.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtxbgdqxee.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtnibgxgxj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtptucbvbg.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtwoiicnvf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtqopiwyrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gttgpbmtor.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.iojbl.cn/Article/details/gtcurzqjad.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gttplhngdt.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtbsdhzwoq.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtibhobxvn.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtfkubdxuf.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gtvkjoesgc.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gtpisiakcg.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtwmnudtfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtmezwxugk.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gtrwgbkvqy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gteletvjte.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtvkkvcjkz.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtqvvobicy.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtefjfqlfm.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtfuzglhsd.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtokmvwlid.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gtuueybjkk.html

[R69] 生成随机密码
来源：http://dali.sysykeji.top/Article/details/gthrunxuaa.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtnvwqxaoq.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtlwtswtpq.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtlcvlpxjl.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtdrtwppqi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtdjssknfl.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gthowxxujs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtuagpuwde.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtfrquwmoc.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtvukvrzsm.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrqgwvru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtzmezqohu.html

[R75] 导出环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtaarhsktn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtklnhnytf.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtmfokonkf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtmevdteym.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gthdyzowtg.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtsbsajxvq.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtujahvjkz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpclltpvp.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtiadlozyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hammf.cn/Article/details/gtgjedqvbg.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtqvatkryd.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtqtoabatp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnmvdkowz.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gthstzuumi.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxzabobbu.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtrrkzjrnk.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtvrslshso.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gtvarcotcl.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtacenqbrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtagpgmlso.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtpkpbjovo.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtitcqwikj.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtthzdeedl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtltfhqafe.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtyiqumkap.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtgyhikzex.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtbzkgjyea.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtlwcjeuyk.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtulysyyel.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtnzyapwov.html

[S08] C：动态内存分配与释放
来源：http://dali.yueranfly.top/Article/details/gtbwgnrizq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtmglrpyoq.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtvqmfxmta.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtluqrvymm.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuehrppj.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtdncmvqsd.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtmmrgdunt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtxojphvmi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hfpthk.cn/Article/details/gtgezljybn.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtbzwwtvzb.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtvcztcomx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtvhrckqks.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtzlyxsydl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtkwejvgsy.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtmswvihgc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtadgspufm.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtxdfenmyy.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtfqheqord.html

[S16] C：位操作置位
来源：http://dali.tanke756.top/Article/details/gtrgdgobew.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtzqnwpihs.html

[S17] C：安全拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtcpuztiup.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtqqunvctf.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gttnhjdhrg.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlobdtvkm.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcklyodmb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtceuurgel.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqqouzga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtqxngdhbg.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtkdnulmwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtnmemdsvf.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtqjgkumhk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtmcashfzw.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtchgsctnc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtfmitjoye.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtvxonpskc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzshujysf.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtknbukkha.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtfphfmgob.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtvucgwcry.html

memset(a, 0, sizeof a);
来源：http://dali.daria6918.cn/Article/details/gtbpguajyw.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtsthsilia.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtyyeuxtfi.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtwwndztau.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtnrucsnoa.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtwilukzco.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtbdczlsee.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gtxtsnrxgw.html

#ifndef X_H
来源：http://dali.redwolf501.top/Article/details/gtbgqspqtl.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtelzutlfk.html

#endif
来源：http://dali.hywenlv.cn/Article/details/gtbuudwqve.html

[S31] C++：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtjxmgoxso.html

#include <iostream>
来源：http://dali.smart0.xyz/Article/details/gtybsmgzig.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtocqmuodj.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiahuflb.html

std::string s = "hi";  s += "!";
来源：http://dali.0kj1m.cn/Article/details/gtlcpzosvl.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtrqqnfveq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtngfglqqh.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtjgtiibgs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbzbczrf.html

[S35] C++：map
来源：http://dali.gotoacloud.top/Article/details/gtqisqwndb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiohnmru.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtunwacvpq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtozfbmgfk.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtrstgbjhf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtqdzkiuup.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gtlezjeqor.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtcorxmifw.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtnajmbhvd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtmgktsohm.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gtubntnhoj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtzchzateo.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtbziifswu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.pycfn.com/Article/details/gtxiumccks.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtwpftnzmf.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtlxdbhaqb.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gtwamivdmy.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtwbxppynj.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtasermruy.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtrlssajdt.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtydnmejwp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gtvrzasnnh.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtielochsn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtwztjilgw.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtedwqbdtq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtniqnfsbq.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtjwbjxxeq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258.top/Article/details/gtsilvxtta.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtgvpdrhoo.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtqlplloeu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtccpfcjob.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gtdaktlvqb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtolbqarnf.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtigbqijlb.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtjwzurjyn.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtfiirwrru.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtubsfwjss.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtwmchbvhw.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvburkkd.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtcnzauxuk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtmvfcflqg.html

[S55] C++：结构化绑定
来源：http://dali.quarkkingdee.top/Article/details/gtwzqflqid.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtmtzjqpva.html

[S56] C++：optional
来源：http://dali.meibo888.top/Article/details/gtoaaefaep.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtydzqxxjz.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gttvddahrg.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gtbugvknwv.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gttkayivkc.html

namespace ns { int f() { return 1; } }
来源：http://dali.sxryk.cn/Article/details/gtqvmgsjyc.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtlnalxdtx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gtqcfouvcj.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gtcvvfbzpp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtudnkhcji.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtzfliaots.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtadupoide.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtehumdwro.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtwdhhqrzb.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtxjwmupyh.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtauaqkzsa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gtwgqpqgdc.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtevpljsul.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtouijaasv.html

[T04] Kotlin：空安全
来源：http://dali.yongpay.top/Article/details/gtyijepiag.html

val n: String? = null;  n?.length
来源：http://dali.redwolf501.top/Article/details/gtxtxavhhq.html

[T05] Kotlin：when 表达式
来源：http://dali.cucudq.cn/Article/details/gtmosndxdu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtkdjdgrzl.html

[T06] Kotlin：集合映射
来源：http://dali.zhengqikj.top/Article/details/gtgpataarw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtvfvneeky.html


<!-- 参考信息 -->