代发 wailian999

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtxmlkfnzh.html

[R08] 数值比较
来源：http://dali.jianghu66.top/Article/details/gtyqkusrat.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtuvrrqndn.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtffrlhtan.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtwihqqndb.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtlhgjexpr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtaebybire.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gtabglundv.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gthxyvgrve.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gtlocmqdnd.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gthkfiycal.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtxjlnfjvc.html

esac
来源：http://dali.jyoumei.cn/Article/details/gtjpznrjwb.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtkbqhzsla.html

for f in *.txt; do echo "$f"; done
来源：http://dali.c1oappe.top/Article/details/gtmgxkkuav.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtspcugqun.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtentawifw.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtvvgaxpot.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtqujwvgha.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtohynbkrx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gthdwgzuqz.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtujctiqkk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtduhbtqfv.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtpccidhlo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtxxnquydj.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtubbqstgs.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdujtbtlf.html

[R19] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtbdcfpdnf.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtkihxzprz.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gtshdgwpen.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkcbsgpm.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtyvqsvzbt.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtazxohduc.html

[R22] 截取子串
来源：http://dali.xziqi.cn/Article/details/gtqvpzwbht.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gttavdcfat.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtcstocsvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtdfjofqsa.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gthskfloji.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtgtrliema.html

[R25] 去后缀 / 去前缀
来源：http://dali.quarkkingdee.top/Article/details/gtpbrsemyf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtqwyrnlxd.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gtunivfahw.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtzrdxsphq.html

[R27] 算术展开
来源：http://dali.jianghu66.top/Article/details/gtvfefsjcc.html

echo $((1 + 2 * 3))
来源：http://dali.hysaishi.cn/Article/details/gtdtixmahw.html

[R28] 浮点运算
来源：http://dali.yuanzhike.top/Article/details/gtpvgwsipl.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gtuqdlwyxi.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtmcqjenuj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtctlgfxmw.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtyniemjin.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtxwwlicde.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gthdqqghhe.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtxsayqdid.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtbgczfezc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtkskmgkil.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtdssekuba.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gtbxsyhenu.html

[R34] 退出时清理
来源：http://dali.zdqjudy.top/Article/details/gtcxovhdef.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtoyxrgzfj.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtkapmtlnr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xziqi.cn/Article/details/gtrovufjpo.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtddekzgbw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtlntwgrtw.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtrnxzpvsu.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gttyfjoati.html

[R38] 管道串联
来源：http://dali.wangdashe.top/Article/details/gtqbfdmfuw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtlfdaltfm.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtxsermrhj.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtfbuwlpri.html

[R40] 追加写日志
来源：http://dali.kuanghao11.cn/Article/details/gtlzyendev.html

echo "log" >> out.log
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaabievx.html

[R41] 丢弃输出
来源：http://dali.hnxiangtu.top/Article/details/gtjrquwfjw.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gtusyfkxge.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtyzitiksa.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtmcscygrb.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtifwgndas.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtqqjxbghd.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtvpicfgpo.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtomappcif.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtfmcgqraz.html

find . -name "*.tmp" -delete
来源：http://dali.sweek.top/Article/details/gthvmcjhxd.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtfwkfdtgm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtqereyzgz.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtnbtnndfp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtnpuldjyz.html

[R48] awk 取指定列
来源：http://dali.yongpay.top/Article/details/gtzrbgqgsg.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtaitpkjmq.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gtaywwzvub.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gtlxaembkr.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtvktgflqe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtvtfzkpxw.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gtsftlrtrp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtcfykjnpj.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtzmnwnier.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gttanggier.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblhjqubb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtcowojnyj.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtppdzxflg.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtlcsreiyo.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gteqiwawok.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cdnleiting.top/Article/details/gthwuhguvj.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtrmjqnzhn.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtgtlvugvg.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtqflksiud.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtaghfmbmx.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtaqwzhigg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtkfmmgnbj.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtgcwcirmd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtpjozuvzm.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gttucdjqjb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtirlgtyhm.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gtgtsazura.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtlqvrxujf.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gtcqyjkvpu.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gtsuafxonk.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtcbpedezo.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtfhgzqebh.html

[R64] 结束进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrllmawn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gtbnwwgsii.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gtkhourodn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtsxwonzfi.html

[R66] 定时任务
来源：http://dali.sxryk.cn/Article/details/gtlhapmhcy.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtdwhhvsry.html

[R67] 生成随机十六进制串
来源：http://dali.nanxinkj.top/Article/details/gtoqavirab.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtoyrrrkhp.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtbbulbvyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtnuxtxszx.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtbwnatuen.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtinyyokau.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gtakavdvjh.html

date +%s;  date -d @1700000000
来源：http://dali.gaohongyu789.top/Article/details/gtbogenlyf.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtzkdzsajs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtwvhllxmx.html

[R72] 等待端口就绪
来源：http://dali.guowangkeji.top/Article/details/gtvtqvwptd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtjkmzwehl.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gtdvtjzgti.html

split -l 1000 big.log part_
来源：http://dali.chenjidiqi.icu/Article/details/gtnqznhddy.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtdcbjicra.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtziqdcwwc.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtswubcewa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yvedp.cn/Article/details/gtlcwssgvr.html

[R76] 使用临时文件
来源：http://dali.hongshengwenyu.top/Article/details/gtrwelpuuc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtdhzoutey.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtvdguhxut.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclsceufq.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtkdcwrqmb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtiibcxmyg.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtjphaabyw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gttlwnyrgm.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gturxdkzjr.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtdqfznfyi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehmqtbuv.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtxepdjiog.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gttoyzpiwu.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtosrdzguc.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtepjaxfyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtmfxslwap.html

[S02] C：变量与格式化输出
来源：http://dali.fengsongda.top/Article/details/gtlmoglnds.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gthnwojaye.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtgwypbqxs.html

int x; scanf("%d", &x);
来源：http://dali.bjfxy.top/Article/details/gtnnhtzhms.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtcmzycvlq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgfzy.top/Article/details/gtftjjjoes.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gthubqlxck.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtepgnnuac.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtctqlmnot.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtgqntbvbf.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtycaqrzmf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtpgqdcvod.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtxmylugnz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtmgbuoaxb.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtxjhahzua.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtrrpsnnya.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtrmpvkyan.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtoughxkej.html

[S11] C：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gthlaghfey.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtubagkgjt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtxgbodbmu.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtortknacs.html

[S12] C：写文件
来源：http://dali.gotoacloud.top/Article/details/gtykrtxgyr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gtcfmbaekq.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtgyynaaei.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gthreydxcs.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gthofmfmof.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtzojydxnl.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtpyaupxsa.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtvsipmsir.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtgkkdyinw.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtqoehobfe.html

[S17] C：安全拼接字符串
来源：http://dali.hammf.cn/Article/details/gtxxhorney.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtlaifmaoc.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpipmnne.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtucrnvanq.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtfdkoklmz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtxufbsabv.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtdspiytxz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtrpxbdghx.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtwqspryzy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtmtdqfauo.html

[S22] C：字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtodjizrpp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtfwbpqvkm.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtpoxifrsl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfalgtins.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtlhqjworx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuanzx.com/Article/details/gtoasalqte.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gthjahxzzs.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtcoalagkg.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtfzszeibe.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtwqgjmygz.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtbcadqxmj.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gteoucjudv.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtsapqskee.html

static int counter = 0;
来源：http://dali.svipenyu.cn/Article/details/gtwqnegjun.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtqpyeqjqv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtvflcovze.html

[S30] C：头文件保护
来源：http://dali.aizwys.cn/Article/details/gtadegljbq.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gttzxdmzuh.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gtdlfkbfgp.html

#endif
来源：http://dali.ydzc1.top/Article/details/gthyqncrhv.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtsnxvimmx.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtqnhhgkox.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtflprtesy.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gtwpaduspd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtxzdahjwx.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtgzxsnmrw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtztoszgcr.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gtrdxedpma.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gtzpddshlc.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtfndbhlon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtxdvtpjsh.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtyyuvujtt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtwtpaqeka.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtnaacenwt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtixjjpybt.html

[S38] C++：排序
来源：http://dali.0kj1m.cn/Article/details/gtucpjxllt.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtmeziyage.html

[S39] C++：自定义比较器排序
来源：http://dali.guannengcc.top/Article/details/gtekqvdxbq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gtgmgdgvwt.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtsazzsfkz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtrmquzxgk.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtmbdngpkv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jyoumei.cn/Article/details/gtaaurbrbd.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtskgwcabh.html

class B : public Base { public: void f() override {} };
来源：http://dali.sxryk.cn/Article/details/gtlmtwhwby.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gthpenxgnf.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtzgpkkzlp.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gthbkvqiit.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gtiyyywjne.html

[S45] C++：lambda
来源：http://dali.cdnleiting.top/Article/details/gtwlkzlpcn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gtydqtgycg.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtyalhpftx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtkzeptfyt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtcnbipvtc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenzaomai.com/Article/details/gtocjwwmaq.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtftdbwojv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtitmdcibh.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfayafmr.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwzytrrh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gtdtmfhkgk.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtlxhhrbhz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtubdaorap.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtdywuxxxq.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtmvozcjcs.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtvobykbtw.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gtaxvhnlwt.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtphkbrdgs.html

std::vector<int> w = std::move(v);
来源：http://dali.kuanghao11.cn/Article/details/gtbycgubtb.html

[S54] C++：异常处理
来源：http://dali.cqqwz.cn/Article/details/gtnkwjcjsg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvjcutmt.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtynhskssl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gthovgqkel.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtecvekrsz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtromddxgc.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtryxyohtq.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtjvvleurc.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtbgtfgpyv.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtxvvajgkj.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtfpntvsxj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtodscobla.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtktfxcagv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtswbwlcct.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtonayvcvq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnonhmmy.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtluncmhoc.html

[T01] Kotlin：Hello World
来源：http://dali.aizwys.cn/Article/details/gtuiyxqtdp.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtugwzkyeq.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtllmiqhlh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cqqwz.cn/Article/details/gtxksikhpc.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtvgjryssu.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtwlotzpdo.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtzvknjvdu.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtzhrrhjxj.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtbklzuinp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyxstzft.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtwyktvgso.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtivlnjnaf.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtgqqsxdyp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtydkqgouo.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtbikdqudz.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtfbsqlklh.html


<!-- 参考信息 -->