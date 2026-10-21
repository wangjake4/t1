代发 wailian999

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtwzszocyx.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gtnnucygtm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtmdeibbjn.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtshrogzrx.html

case "$1" in
来源：http://dali.shangyingyoupin.top/Article/details/gtqwnvolit.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtisqddymk.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngqawepf.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtikfjqzwl.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtrpradqdj.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gtbofvcnya.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtahgfsubc.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtttxngdmt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gteqhmossm.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaiceseeb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.haohaochexian.top/Article/details/gtzrdwnwud.html

[R15] while 逐行读文件
来源：http://dali.yj202588.top/Article/details/gtorsjzbui.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.vqdsnc.cn/Article/details/gtvnlrkezh.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gtkvyzvaon.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtpndxysia.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtcgklhsda.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtipaksrdi.html

[R18] 遍历数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohlrqpwg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtjhqqgqud.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtwwgnmeia.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gtbiocumlo.html

[R20] 关联数组（字典）
来源：http://dali.cdnleiting.top/Article/details/gtdeivpxuu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtotmcypqw.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtkymxwiaa.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseoyohec.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtcepxzpvg.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtpsglqcfe.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtogtcvpqc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtrmfbkibw.html

[R24] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhzjtvck.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtsmofuxls.html

[R25] 去后缀 / 去前缀
来源：http://dali.feifeiyinyue.top/Article/details/gtlzhzzvfm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.havefunace.top/Article/details/gtriymufra.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtxrjazwkq.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnysfldx.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gtwullqfqt.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gthcvtbttz.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtgxpgvglr.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gtaafrfdzm.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gttqxdalrp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtghwqadqn.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtnwsdhxsz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gtunzyzzyx.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtmvvykpbw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqcgvbdjs.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gthnvewrac.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtbsiocwfp.html

[R33] 捕获错误并提示行号
来源：http://dali.mhx1999.top/Article/details/gtqziqwsjg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj202588.top/Article/details/gtazhuofzy.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gttjxcaiuv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gthbjgdqpy.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gticjijxaa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtyvfcrwjp.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gtvwyzgazp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gtzeyjeqrq.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtwwgiijwj.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowxvimfe.html

[R38] 管道串联
来源：http://dali.quarkkingdee.top/Article/details/gtereqckxp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtcsbelvjy.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtxuqtsaiw.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtitdfszfq.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gtjtxvpcum.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtbprafshx.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtjavtodvh.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtutyfrmxz.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtuqgibxgz.html

wc -l < a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdhpedae.html

[R43] 按名字查找文件
来源：http://dali.cucudq.cn/Article/details/gtthsufthh.html

find . -name "*.log" -type f
来源：http://dali.havefunace.top/Article/details/gthcgiveql.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtymllmyie.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtqvtjugnp.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtwftvxdkx.html

find . -name "*.tmp" -delete
来源：http://dali.xinyue.icu/Article/details/gtisbcosav.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtzsxykegj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtwfofuboq.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtreshbavm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtkcxvxwbe.html

[R48] awk 取指定列
来源：http://dali.yuxming.cn/Article/details/gtvmtefsuv.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtrocvrfey.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gtabivtjae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtfhrkmelc.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtvyxfzvjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtbyywbxbc.html

[R51] 排序去重取前几
来源：http://dali.gogol.net.cn/Article/details/gtaznyytgr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtlapdpbbc.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtsnqrmwsu.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtrqwsdhhb.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gtkkaeoqhy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtqnawpwdk.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gtikyzvlqc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gtzpihkaax.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gteagvngpm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtfnscihob.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtmhhtebiy.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtphhfhgnk.html

[R57] 远程执行命令
来源：http://dali.gogol.net.cn/Article/details/gtbwcgzqnt.html

ssh user@host 'uptime'
来源：http://dali.bjfxy.top/Article/details/gtgizbffml.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtwhlkphpj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gtwcmcssqe.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtagevhfmm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtowkqlzmf.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gtnekjkhur.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtukoavcjz.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gtdkdtjedz.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gtzjdxeuzg.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtwibjejsa.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtxunfybag.html

[R63] 内存与进程
来源：http://dali.ydzc1.top/Article/details/gtxgnfxzki.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtppexmyec.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtubwnwdoc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj202588.top/Article/details/gtrxeiwxek.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtqtdtoave.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtmuproxlj.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvgkvjzy.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtrktpnjkv.html

[R67] 生成随机十六进制串
来源：http://dali.zhoulong.xyz/Article/details/gtyapizcix.html

openssl rand -hex 16
来源：http://dali.xuetiantiany.cn/Article/details/gthagkkohv.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtjuygxgae.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtjvlruzgs.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtzhmoynrr.html

head -c 16 /dev/urandom | base64
来源：http://dali.ivvv.top/Article/details/gtiuztmrkb.html

[R70] 时间戳与互转
来源：http://dali.sysykeji.top/Article/details/gtoouxvwxu.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtekfiygax.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtukuagpca.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tanke756.top/Article/details/gtcqzztnxs.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtilywyjon.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtpgeckfeo.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtltocvodb.html

split -l 1000 big.log part_
来源：http://dali.shuidangran.top/Article/details/gtntchaszh.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtwakvpdam.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtcvandrqb.html

[R75] 导出环境变量
来源：http://dali.meibo888.top/Article/details/gtqjudzjav.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtczmlbjwf.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtuifeegug.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gttmblwdvx.html

[R77] 读取用户输入
来源：http://dali.feifeiyinyue.top/Article/details/gtvkgjrqpq.html

read -rp "请输入: " ans
来源：http://dali.pengpengdd.cyou/Article/details/gtjvjlomsa.html

[R78] 交互式菜单
来源：http://dali.ybcxt.top/Article/details/gtxiijekkn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtrajfpaps.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtusxwjaaw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtaagaqknn.html

[R80] 查看脚本执行耗时
来源：http://dali.tian-w.cn/Article/details/gtzlqfcnia.html

time ./run.sh
来源：http://dali.316326.xyz/Article/details/gtoxjzcufv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtaixxnfyx.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtajqymvkp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtntansilf.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgohzayx.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtqfgqtfjm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtmdktnjxj.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtukutyuih.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtcrlliukw.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtuctkymcm.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtmxjqtyoj.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtcxvsqmkg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtjinetqph.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gttqlywtzt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmphqndtm.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtaiuyusjd.html

strcmp(a, b) == 0
来源：http://dali.wangdashe.top/Article/details/gtejebofzl.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtevkrvyfa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtnvqikepd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhiwuduotai.top/Article/details/gttehkxxjt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ppjwa.cn/Article/details/gtlqgvlxma.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtjxwiiprm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtnpebfgox.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gtjenhzpqh.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gtmdvvtbhq.html

[S11] C：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtclljadib.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gthvnmbckf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gthhdkayvg.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtwfngfgrk.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gttbmkwgii.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtrusfayif.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtenoensyw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtvvrhssmi.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtgeytymzl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtsmfrkehe.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtrveksaqk.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gttfudycrf.html

[S16] C：位操作置位
来源：http://dali.daria6918.cn/Article/details/gtdbxfngmy.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelllvszz.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtintkctxj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxggpqtep.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtfabssicu.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gtkdhwhmyf.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqapekxn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gthxjzdubq.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtzydbedso.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtspfenzub.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtmjasgwwm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jianghu66.top/Article/details/gtkcibdkys.html

[S22] C：字符串转数字
来源：http://dali.316326.xyz/Article/details/gtkueecwyi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangdashe.top/Article/details/gtpquozqkk.html

[S23] C：随机数
来源：http://dali.jqgufenzy.top/Article/details/gtavmfbliv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtigywnuos.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtwbzeajpd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtiirugytc.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtqyvqauwd.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gtpdikltid.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtnoxrfuuw.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtrcuganxp.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtqyxcdhip.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtxktmmgkm.html

[S28] C：静态变量
来源：http://dali.shuidangran.top/Article/details/gtukinjqob.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtrhgipdlm.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtcjwdijby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtrofjcfgg.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gttpzkqslk.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtbaplkjfd.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gtiuluhjrf.html

#endif
来源：http://dali.cdnleiting.top/Article/details/gtfrapymmm.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtxtlxlprj.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhfmemhs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtyhabezin.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gttsuywbsf.html

std::string s = "hi";  s += "!";
来源：http://dali.hfpthk.cn/Article/details/gtkenycbja.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtlgoxnbbe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.smart0.xyz/Article/details/gthddsiyap.html

[S34] C++：遍历 vector
来源：http://dali.daxiang520.top/Article/details/gtcsfjmblo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimgubnrn.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtjojvdqad.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtceoagnay.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gtrgssplpz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtrplriqrb.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtzljozjbk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtvnesbthc.html

[S38] C++：排序
来源：http://dali.hfpthk.cn/Article/details/gtamrbnnbv.html

std::sort(v.begin(), v.end());
来源：http://dali.hnqzz.top/Article/details/gtzsalppss.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtnkmhyzfa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gtypuqxrey.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtrqvtyuas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtcqjmcebp.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gtmrabgeef.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxuanxn.top/Article/details/gtsaiexccv.html

[S42] C++：继承与虚函数
来源：http://dali.hfpthk.cn/Article/details/gtenbrbxqv.html

class B : public Base { public: void f() override {} };
来源：http://dali.cucudq.cn/Article/details/gtpbaeluzi.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gtucduqvxw.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtftdqlsot.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtrgxunahx.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtmdkmdfhw.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtloxvxihu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gttaanzmpl.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtujkwhyth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtjitgmbfs.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsudjthxc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gthinzteyp.html

[S48] C++：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtvjexhbmo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtjbxnoaby.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtajxhuedi.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gtiddwgvmx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtamgcakre.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtdoucbsvo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtkujgkphy.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gtlvoolhnn.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtlzajcbjg.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtuuxoapim.html

int size() const noexcept { return n_; }
来源：http://dali.zdqjudy.top/Article/details/gtwxelbglg.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtougxlpso.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gtzerefszb.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtmzkuranl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtyssghays.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovxzahuu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gtsemsjvfc.html

[S56] C++：optional
来源：http://dali.yanxiufei.cn/Article/details/gtgxpdrihk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangdashe.top/Article/details/gtvoohzymy.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtjdubzkye.html

constexpr int N = 10;
来源：http://dali.andypj.xyz/Article/details/gtgqluhotz.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtattabgpk.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgtzggcd.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtbrtolsvd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtntvujkdc.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlrylbeh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtkgokdvst.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmciyptmv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtjieukvth.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlujahjub.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtmcbkkofs.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtgcebxgvl.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtfoeefezm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtiqoxlodk.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gturcddaic.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gttvgmvbxt.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtjxbvxnqq.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtixjalmsa.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtwklbgaqn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gthwovikfy.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtdrkgkrdt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gtydvuglze.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gttguadvad.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtsmcxkuof.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtkfqjiecz.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gttsgzbmvs.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtuarggcnl.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtgqyyggvc.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtjuzsrhdu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gtaeootgoz.html


<!-- 参考信息 -->