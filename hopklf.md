代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtqdplxwbs.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtlpmhvqxz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtkjzcbffl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtygfrmtpm.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtyfmfjbvu.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfoorafkr.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtcngabpar.html

#!/usr/bin/env bash
来源：http://dali.nanxuanxn.top/Article/details/gtvwxuueba.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtnkmdzavj.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtebllkyjs.html

name="Tom"; echo "$name"
来源：http://dali.jqgfzy.top/Article/details/gteuaaurqn.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtepyuizve.html

readonly PI=3.14
来源：http://dali.aibaodan.cn/Article/details/gtcqwundkn.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtuefoebjn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shzxlz.cn/Article/details/gtlapjmkcj.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gtvlngjzsd.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gtduxtqycz.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtvzsmnvjf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gtkzocbgqd.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtqvkmmaom.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtclurggzu.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gttvpemitg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtssoeoovq.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gthyumvzst.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtiahcojpi.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtqbtixrje.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtboxlbbgr.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gtinptqdat.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtfmpjvddx.html

start) echo "启动" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtitthkvhc.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtanubtkiq.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gtgdyvnras.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtzwcjaexf.html

[R12] for 遍历文件
来源：http://dali.hongshengwenyu.top/Article/details/gtdpcpjzdl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gtxbvsqqvv.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtbnttknwv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtssygxnzk.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtretcnddk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtbkelrnkr.html

[R15] while 逐行读文件
来源：http://dali.birdmap.top/Article/details/gtnzwksfhm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gttmwexrll.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtasslqbdz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gttjdixbay.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gtpyxiojqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sxryk.cn/Article/details/gtglowgpho.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtgfwdjcez.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxinkj.top/Article/details/gtorjetdjc.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtykgyzynn.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtmdpwqrpm.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gttjqvgyke.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gtxoojtzwb.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtafjoubwt.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtojsygeno.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtudotbfzf.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtijnnmyye.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtfafmpafk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gttooqubqf.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtoyfhxdin.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gtjuygrcyy.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtiwudczos.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtifaoofxn.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gtgmvinubc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtzjkrzyzp.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtdswdvdgh.html

echo $((1 + 2 * 3))
来源：http://dali.gogol.net.cn/Article/details/gtskbiidmz.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtqivjuwvg.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcqgxxwl.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosofbhmd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gtlcgxwnpd.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gtbxifqref.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cqqwz.cn/Article/details/gtquqidhmj.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtbkknqoma.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtrmvkqqer.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtxmqnzrmz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gthlpbaikn.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtxhofwheb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtexpvankn.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtfgsfyioa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtzlhmlnhv.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtngfrecvj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmniumezr.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtnzngdnvc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gtthsmnaan.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtpjasaxyt.html

files=$(ls -1)
来源：http://dali.chenlongwang.top/Article/details/gtpjbjvedf.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gtlvwqbtyv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gttilrrvbf.html

[R39] 重定向标准输出与错误
来源：http://dali.feifeiyinyue.top/Article/details/gtdkyvelzt.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gturhnoavx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gtyxpzriru.html

echo "log" >> out.log
来源：http://dali.dianchejie.cn/Article/details/gtfbfxdskl.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbtzekmp.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtqvbrhswq.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtlxtolgnv.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtqgndudaz.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtwahoxjyw.html

find . -name "*.log" -type f
来源：http://dali.sufxvd.cn/Article/details/gtwmxylyia.html

[R44] 按修改时间查找
来源：http://dali.tanke756.top/Article/details/gtewccbanc.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtnasmzknz.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtixczkekx.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gttgviplru.html

[R46] 递归替换文件内容
来源：http://dali.0kj1m.cn/Article/details/gtgzdnqsna.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnxiangtu.top/Article/details/gtjgfamhvr.html

[R47] sed 单行替换
来源：http://dali.nwbrower.top/Article/details/gtovegvhen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtklkmtnzx.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gtjrrvopzi.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtrokwebsa.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtukedfxbx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtftrbokmz.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtcrqzibyc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtyhesbepq.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtopkqfiza.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yueranfly.top/Article/details/gtlpukncct.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtyyplqxxa.html

wc -l a.txt
来源：http://dali.bjfxy.top/Article/details/gttapfkttp.html

[R53] 查看文件头与实时尾
来源：http://dali.yongpay.top/Article/details/gtdxyzhkta.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtxgyyqxjs.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtazklgvku.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtkveaflht.html

[R55] 压缩与解压
来源：http://dali.daxiang520.top/Article/details/gtszvosqxc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.birdmap.top/Article/details/gtrnapgcqa.html

[R56] 远程拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtcwcxxzzm.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtbpebfrkg.html

[R57] 远程执行命令
来源：http://dali.cucudq.cn/Article/details/gtbtgovpfb.html

ssh user@host 'uptime'
来源：http://dali.chenzaomai.com/Article/details/gtdmibiapp.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtmwscjnes.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtiaolvjen.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtyqpkkogd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gtttrizqzr.html

[R60] 只看 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtrdsnpszy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbktvasv.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtaoqamjyu.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gtomldlyvf.html

[R62] 找最占空间的文件
来源：http://dali.zhixingplan.top/Article/details/gtezhitsfc.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtfbiqtmvg.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtfnhcchrw.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtsareczvk.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtlndgwfhu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gtkhslvnlv.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gtauretbwa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtbojkdhow.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtnpjowdwt.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtxvsuswsh.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtbmyyslfd.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gteoqigrks.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gttbaotvrv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gtwyzglxtt.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtixywsrpm.html

head -c 16 /dev/urandom | base64
来源：http://dali.xylfe.cn/Article/details/gtcmvihmhp.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtysujmxpb.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gtobgphqay.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gtwhyumzsl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtbnjdyzav.html

[R72] 等待端口就绪
来源：http://dali.nanxuanxn.top/Article/details/gtoaojwsve.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gtvlspwbmf.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtmegcbuer.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtgcxwvkpu.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gtrngnpeqj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtpwefynxy.html

[R75] 导出环境变量
来源：http://dali.hywenlv.cn/Article/details/gtiscfjmji.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtxmjasbof.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gtdtgycmqi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtglryswds.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkggirhu.html

read -rp "请输入: " ans
来源：http://dali.hnxiangtu.top/Article/details/gtzcjhytpg.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtytfhvsun.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.9152youxi.cn/Article/details/gthwtrfwdn.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtakjmzifi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtsxxpvcie.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtkzvvybiy.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtfsmlaprh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtbvmanvgi.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtyuycsnjz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjtuulpyw.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtxccdgiab.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtzlnxnnaf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtbtigrfta.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtxnxzgogi.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtgleeykml.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtmpzaakgg.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gthjwuqvba.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtuizzqoyz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gtcifvoygp.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtemilswna.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtxwivqrjw.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gttdnvxjim.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gtussctjda.html

[S07] C：数组遍历求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcsxitzl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtomnhkvqc.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtqjdzkvtn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtxeygdoqd.html

[S09] C：结构体定义与初始化
来源：http://dali.gaohongyu789.top/Article/details/gtprmbxejg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtwehwitgx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtzqzoukdy.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtcpibdzgr.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtouazbrpw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtaggoybte.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.c1oappe.top/Article/details/gtlgdgthxt.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtxswsoqjm.html

[S12] C：写文件
来源：http://dali.nwbrower.top/Article/details/gtnltinaqy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtxcerxeoc.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtjadsdusu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gttdaerezj.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gttbvwljwj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtatkjvnyw.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtxqymszqk.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtsvptyvab.html

[S16] C：位操作置位
来源：http://dali.jinqigfzy.top/Article/details/gtqzyqsyvw.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtygtuemjr.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkkmmech.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtnukqmhyo.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtwqfndrwz.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtnheizfku.html

[S19] C：快速排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscvgsuhh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtrqduyusd.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gttlrvyudv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtwtqfcsbv.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gtdznfkavl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangdashe.top/Article/details/gtddwfious.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtasmmfaiu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ybcxt.top/Article/details/gtykruccvg.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtqevgzvwv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gthohjoavt.html

[S24] C：获取本地时间
来源：http://dali.cheryme.top/Article/details/gtotqcktzh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtujagfkva.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtyangzwot.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtjvbvjgqj.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtntbbexiq.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtcrgacktp.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtqfwzczcl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtbrxybhzc.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtrtqicryw.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtwlxpfynb.html

[S29] C：变参函数
来源：http://dali.wangshuangyany.cn/Article/details/gthhzrkkml.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hfpthk.cn/Article/details/gtdzeanfgo.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gthhijktki.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtrfjpucfj.html

#define X_H
来源：http://dali.jyoumei.cn/Article/details/gtajyprxct.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtwoapslol.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtjjayjtjm.html

#include <iostream>
来源：http://dali.guowangkeji.top/Article/details/gtpipkwfva.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.smart0.xyz/Article/details/gtatiyrvhv.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gthtwwxbnb.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtnvbjxeqk.html

[S33] C++：vector 增删
来源：http://dali.fengsongda.top/Article/details/gthimirqeq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtwlwunlek.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtabtfllwa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtftliskgu.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtagfqpmmk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtuythgphs.html

[S36] C++：unordered_map
来源：http://dali.yj20258888.top/Article/details/gthazamita.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiulsrvqq.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gthiomeehm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.redwolf501.top/Article/details/gtqkiowwhe.html

[S38] C++：排序
来源：http://dali.sufxvd.cn/Article/details/gtybjqyruy.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtvyvhzvvw.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtzxjmbnpn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtszyyrhzg.html

[S40] C++：查找元素
来源：http://dali.chenjidiqi.icu/Article/details/gtspcebkmk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtrvkrayna.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeqaswbx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtuepujtlb.html

[S42] C++：继承与虚函数
来源：http://dali.jyoumei.cn/Article/details/gtwuftaclk.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtmpzcynoe.html

[S43] C++：智能指针
来源：http://dali.chenjidiqi.icu/Article/details/gtgfqieeti.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtfhswowht.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtlyxdokax.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtqxbuuabb.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gteesltzwx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigfzy.top/Article/details/gtjfhqcazw.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtxtijrtmd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jiagoushi.top/Article/details/gtearsltze.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtrhgulxcn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hammf.cn/Article/details/gtatwkfint.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtzguwxhhp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtyaqtuhtg.html

while (std::getline(in, line)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtnffmizax.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtcghsggpe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtfwxxufux.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtclebsmfk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtczodvyev.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwnxrvbe.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtdlglxodq.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtxrjswfdx.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtlptmuuuv.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtsyumkbfe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gtjucjccwj.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gtffoaznvz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtwfgemcgr.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtsdrqlenw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckcimuli.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtsmlzyjcc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gtftrzmzfs.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gthekvmwae.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtrrhpefxq.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtczicfwei.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gtfnulvvqr.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gtewdmxmml.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtrhncxvob.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtghvwgrjw.html


<!-- 参考信息 -->