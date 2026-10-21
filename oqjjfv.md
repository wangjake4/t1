代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtccdecssv.html

[Q90] 生成序号列
来源：http://dali.nanxuanxn.top/Article/details/gttbgtnbzf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzngyituo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttndznkep.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtccjzguas.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwrxyrkha.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtckfbtdfs.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtexxnlctl.html

set -euo pipefail
来源：http://dali.meibo888.top/Article/details/gtvgzwxllk.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtybkrsscr.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolyftnpx.html

[R03] 只读变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggjmrkrk.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenrhroys.html

[R04] 位置参数
来源：http://dali.jqgfzy.top/Article/details/gtywlixqvr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtjlonynym.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gthpplhzij.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtgzhiwzve.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtuijcwylf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzgefxjbi.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtddrubdhz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtrracsips.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtjfukjinr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtwfkehciy.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtfarngyar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtnenxgbxz.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtcdjysgzi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtfpnotphb.html

[R11] case 多分支
来源：http://dali.snrcjt.cn/Article/details/gtzqfbrrlm.html

case "$1" in
来源：http://dali.jianghu66.top/Article/details/gtgelknppu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtqkpikvjt.html

stop)  echo "停止" ;;
来源：http://dali.shzxlz.cn/Article/details/gtuduoezba.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gtdadswqdf.html

esac
来源：http://dali.meibo888.top/Article/details/gtcekjfobo.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gthyfzhyug.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtsvvmqddw.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtvcanwhkk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtoagmjqhi.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gtprfyobly.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtjgjlkugu.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdzwaolh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gtqkqxeaoo.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtpkiizitn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gtmhjgfvmt.html

[R17] 数组定义与取值
来源：http://dali.nanxuanxn.top/Article/details/gthcnbyzdr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtgbagkqmf.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtbmhtdtme.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtazqhxhyj.html

[R19] 数组长度
来源：http://dali.shuidangran.top/Article/details/gtmhoavvsk.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtcijrkieh.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gttaxpstcc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.0kj1m.cn/Article/details/gtxpgvvmmm.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtxmdjtwzw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtspketvvy.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtccnhkjcr.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtcnalsysr.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsyxcqszm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtgezlqjzo.html

[R24] 大小写转换
来源：http://dali.smart0.xyz/Article/details/gtndfablbv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sysykeji.top/Article/details/gtezvlqwrm.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtveqsvzqy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtpfkaaabh.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gtyfnreooa.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gtygqhydqg.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtipkhewcq.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtoyxzwfuu.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtijslxngw.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtrmyivwtm.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtraujthxo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtvewszure.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtnvznpmki.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtgybucymk.html

[R31] 局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtobmtosue.html

f() { local x=1; echo "$x"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqgcfpygy.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxddjfpp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtqtjoaujs.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gtgjyyiybh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtarsrgvik.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtbbvoaqlk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gttcuoewlc.html

[R35] 后台执行并等待
来源：http://dali.smart0.xyz/Article/details/gtmenkbbjh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gthrjzqzoh.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gtzuxknnbc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtnjbxcjyv.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtqfwnrilu.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtsqdcmhtq.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gtksfbhvrx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.smart0.xyz/Article/details/gtcvtjcgky.html

[R39] 重定向标准输出与错误
来源：http://dali.yuanzhike.top/Article/details/gtoalfblja.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtcehbsfts.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtsqebggke.html

echo "log" >> out.log
来源：http://dali.zhixingplan.top/Article/details/gtrrbkhoey.html

[R41] 丢弃输出
来源：http://dali.hywenlv.cn/Article/details/gteczeqmul.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnchndgv.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucswnhui.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gthkiglvus.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtgweidkdc.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtykaoshii.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gtotacuicn.html

find . -mtime -7 -type f
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocinkcfq.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtfaqhbsnn.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtqqrjtivt.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtvmccxwtc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtektbslgj.html

[R47] sed 单行替换
来源：http://dali.aibaodan.cn/Article/details/gtzsgeixov.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gttgkvwbye.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtyojjfyfv.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtpxkeuctw.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtnlszfnie.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtzghabqzd.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtqcqebvgc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hammf.cn/Article/details/gtqkkvohom.html

[R51] 排序去重取前几
来源：http://dali.c1oappe.top/Article/details/gtwbzfhxal.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtbdlxmcri.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsvwiaug.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtyxafbojc.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtmolyfcqd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtbemwuvjb.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gtxqdprrer.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gteliqubwi.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxaihevbg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtreevbzzf.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtvmwdhixc.html

scp file user@host:/path/
来源：http://dali.shanyushiyangtech.top/Article/details/gtiucgvyfq.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtrqhisveq.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gttjluytvf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtclfkcwoq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gtyuerbwpd.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtiiliwqsj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtwwourmhe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gttijdcckh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yvedp.cn/Article/details/gtjgnrcngg.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtxdvrerhd.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtsewwaqdz.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gtuawejwbe.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtwemofekq.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtfjyozlqe.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtgkwerirz.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gthjmiaxbz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtysyeycqe.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gteqbhxdqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtgpkyawck.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkeiiccdx.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtjbqsjhoj.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtwbweesme.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtljglimzy.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gthlutopve.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtvkktwzvl.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gtpvnjtlzu.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvqwfivl.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gteyxwqvmo.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtynjvrmcf.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtsyfaxxce.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtwovivznk.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtnhfiwzbl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtwbbhjdzb.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtixebrckz.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtvcizqqej.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtiiykhpig.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gtywavwifw.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtzfytzbrs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtrafwvfgc.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtcohmmuml.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtythqmigx.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtfzevqajl.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtwnnhifga.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtnvjgrtlk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxuanxn.top/Article/details/gtddgpfcdy.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtordutwff.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtldzkpbvw.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtgcytnzsr.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtrhfljeob.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbpdrncqb.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtbhcedqdu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtorvwsoew.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtnaxkpkfs.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtbbwfznfb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtfxcykceg.html

[S02] C：变量与格式化输出
来源：http://dali.zhongyouzk.top/Article/details/gtnnyzykko.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtqaijzkls.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtgbohlhkl.html

int x; scanf("%d", &x);
来源：http://dali.cqqwz.cn/Article/details/gtpcotmbsh.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtctqysksb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtvtbkhgsj.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrdiitdr.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtpeywwkry.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gtkzlvbhrz.html

strcmp(a, b) == 0
来源：http://dali.meibo888.top/Article/details/gtmtyypyyg.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtuobfyawg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gttpdderep.html

[S08] C：动态内存分配与释放
来源：http://dali.yj202588.top/Article/details/gtoxjotqpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtmvxglpqv.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gtkelahuhj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtbqlysugh.html

[S10] C：指针与解引用
来源：http://dali.smart0.xyz/Article/details/gtzxuqcmux.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdkymngd.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtsojpfwsq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtkgwjsepl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtrqncbxtm.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtpmjbwyts.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtjfhlbufh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtxyxgormc.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtoodcdrnp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtqrdqxngg.html

[S14] C：枚举
来源：http://dali.tianlin.xyz/Article/details/gtvgsolhsn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gthbczeftb.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtvcxbsncg.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gteevqunrq.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtrzgqpkkj.html

x |= (1 << 3);
来源：http://dali.zhixingplan.top/Article/details/gtuxmwivtb.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtrfvvcypg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hongshengwenyu.top/Article/details/gtnzvwlshd.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtonhkpvzh.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtqvznuvtg.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtgmcxfkpe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtunfpdsvi.html

[S20] C：二分查找
来源：http://dali.daxiang520.top/Article/details/gtrctpgxzk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtrvhoyurh.html

[S21] C：字符类别判断
来源：http://dali.cqqwz.cn/Article/details/gttqkcxqec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtawcprupp.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtulxvbrzr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.bjfxy.top/Article/details/gtoykyforf.html

[S23] C：随机数
来源：http://dali.guannengcc.top/Article/details/gttxslslur.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.havefunace.top/Article/details/gtidktfjic.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtkslexqqo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.dianchejie.cn/Article/details/gtrpxqxrdl.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtpuiduhgc.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtaaqrabpp.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocgoacag.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gtfiadbbfq.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtvvnsbvdx.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gttgcewjee.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfopcictj.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gtnqoeizno.html

[S29] C：变参函数
来源：http://dali.ivvv.top/Article/details/gtlpwmmxoh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtcupvfyzq.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtvbqwuhxg.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtfowemxji.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtehwjhkjc.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtzxqcokoa.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtbotvhlwc.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gthykzcliy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xziqi.cn/Article/details/gtbsfmmufv.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gtspvmfeim.html

std::string s = "hi";  s += "!";
来源：http://dali.gaohongyu789.top/Article/details/gtwyfuuyms.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gtlfmgpwte.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtobiddkvi.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtmgbptcpr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtbpdkmrfu.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtaflvpqpb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtluhkbmkz.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtbwsdwthw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yongpay.top/Article/details/gtbtzjqcjj.html

[S37] C++：set
来源：http://dali.snrcjt.cn/Article/details/gtzzlsmmtv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtumigezsb.html

[S38] C++：排序
来源：http://dali.zhiwuduotai.top/Article/details/gtonmdvqqy.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gtgvydwdls.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gtjvtqovpq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gttckfmetq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtkfdbkbtw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuanzhike.top/Article/details/gtaptuqrro.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkhmzlton.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtkituqdvs.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gttucedkli.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtwbhpghxj.html

[S43] C++：智能指针
来源：http://dali.hnqzz.top/Article/details/gtjkdtcrbt.html

auto p = std::make_unique<int>(5);
来源：http://dali.bjfxy.top/Article/details/gtonvibigf.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gthywljrzh.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtiyzzxipt.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtgfykyvht.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtnrephgvk.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtyjhkvobp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtftltermo.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtuzlxhozv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtajorpvwr.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtzomfoghh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gtjphptqrj.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtqugnnbtq.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtnxmrqsmf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtcaxpxjgs.html

[S50] C++：格式化数字
来源：http://dali.cashguo.top/Article/details/gtwzvkahbq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtadeixvyq.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gttjvqsgpw.html

static_cast<double>(a) / b
来源：http://dali.jiagoushi.top/Article/details/gtlvxhthcw.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtqgamdmts.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthwxcxxiz.html

[S53] C++：移动语义
来源：http://dali.ydzc1.top/Article/details/gtbovxqqvu.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtgoolnlua.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdratagma.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtdsacqsei.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtqkvoqljv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtqxjpjemy.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtlzquvaed.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjmzfczd.html

[S57] C++：编译期常量
来源：http://dali.yuxming.cn/Article/details/gtjondgugc.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtroeuqyqa.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtntcykeqm.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtjzsdytfw.html

[S59] C++：静态断言
来源：http://dali.wangdashe.top/Article/details/gtiqjkehox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtoadxjlms.html

[S60] C++：遍历并删除元素
来源：http://dali.fengsongda.top/Article/details/gtyrqrumig.html


<!-- 参考信息 -->