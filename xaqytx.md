代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gt2ybxzlhpl.html

[Q90] 生成序号列
来源：http://dali.gogol.net.cn/Article/details/gt2kzvegvcz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gt2lsbmryya.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zzhqntem.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gt2mnfdwpne.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2hvqtqrme.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gt2rxtwtjmh.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gt2zpxrvrid.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gt2ihywhbng.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgvtqndn.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gt2scqjgayu.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gt2vfplosmq.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gt2zowpqosp.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gt2phfkspun.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2xjsryouh.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gt2oqpuxgxd.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gt2nlsexsjl.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2drwmzxdl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gt2izcqqkyo.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gt2rchrmzmj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2bihuyfcb.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpakbcyx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxrdqtbu.html

[R09] 字符串比较
来源：http://dali.iojbl.cn/Article/details/gt2hzjloubi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2jnzhuzua.html

[R10] 正则匹配
来源：http://dali.jyoumei.cn/Article/details/gt2fdyxvfpy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2rmalnkyq.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2jdbdnetx.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gt2uobeuzdg.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2suvdijmo.html

stop)  echo "停止" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2sgexfdlh.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2mfpylvcm.html

esac
来源：http://dali.smart0.xyz/Article/details/gt2pymarveu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdbrtdn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2ylnccpzy.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gt2fhlckvsh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fosksbkg.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jikyooej.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gt2wrgzrjbw.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gt2jtyxdmxg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.snrcjt.cn/Article/details/gt2mgsonrtw.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2dlbqmibh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2wybgvihe.html

[R17] 数组定义与取值
来源：http://dali.cdnleiting.top/Article/details/gt2qwabfura.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gt2emtrhfqs.html

[R18] 遍历数组
来源：http://dali.ivvv.top/Article/details/gt2qyclniqz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxehwsoh.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2raccazdd.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcxavwit.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gt2prwhtajq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2rpkakhpb.html

[R21] 字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2dubiwoia.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gt2neoyzqzi.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2rnprbkre.html

echo "${s:0:5}"
来源：http://dali.guowangkeji.top/Article/details/gt2pxyywmkj.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2olawpznw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2rcocyyrl.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2oxdjojln.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jianghu66.top/Article/details/gt2gutswhas.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2mvazjmce.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2gukdswsb.html

[R26] 命令替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2apjodgty.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzmppozn.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gt2mcvxiftm.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2yvowbtzc.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gt2perxzdhm.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkwlskyq.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gt2gnrtgojl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gt2ulqghvtt.html

[R30] 函数返回状态码
来源：http://dali.0kj1m.cn/Article/details/gt2fbhzzhqi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gt2heomeawx.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2kevvzraj.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gt2slfvryhe.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gt2etoxdrid.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2hacgcweh.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2lfaspuge.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hywenlv.cn/Article/details/gt2jvluxxww.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gt2leueujfs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2mfapjmly.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gt2utudvfmn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cyeaiyjv.html

[R36] 并发执行多个任务
来源：http://dali.quarkkingdee.top/Article/details/gt2hmdjicvr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gt2hsiaulkg.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2vaodmurn.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2zlljxbwp.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gt2rvjojnmr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jyoumei.cn/Article/details/gt2bpnamxws.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gt2znsrqwuf.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gt2dxybpihz.html

[R40] 追加写日志
来源：http://dali.yuanzhike.top/Article/details/gt2rvcmpbuv.html

echo "log" >> out.log
来源：http://dali.zycfv.cn/Article/details/gt2hbcnkvfv.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gt2wqxrioka.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2mqawazpe.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gt2mlpmeqrm.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gt2iawpvnyp.html

[R43] 按名字查找文件
来源：http://dali.andypj.xyz/Article/details/gt2jxlvyflh.html

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2oppjfdab.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2mtnoomcf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjsbhfr.html

[R45] 批量删除
来源：http://dali.ivvv.top/Article/details/gt2lagtozdm.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2cgxtekgo.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gt2bkfxfvxb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2oehxmhxs.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rcgdlres.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gt2niyislra.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpnargml.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2wkiimtxr.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gt2ifvfqzfi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gt2nzjzxjzd.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2kcxasmwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrnzznzk.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2whglhbqq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hfabvsyt.html

[R52] 统计行数
来源：http://dali.haohaochexian.top/Article/details/gt2zdnkacfb.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2rrjwukvi.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gt2qkajdemv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gt2gwyzsmig.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gt2hmiqhckb.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gt2ajreyqxf.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tlobcelz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gt2iranidzw.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gt2xngipkdb.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gt2mnhtfnhx.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2dzycuxdk.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gt2pjpcijom.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gt2tqwiqrmm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2ehwwidoc.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gt2chfvrxqa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gt2wefhpykk.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2lwnvlclo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ocheebka.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztnndann.html

df -h;  du -sh *
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hfszoolr.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gt2fimiojdw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2qyqwtpae.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gt2ctaeurxi.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2ayyckdiv.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gt2meihhpmn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2kjeckrfm.html

[R65] 查看端口占用
来源：http://dali.yj202588.top/Article/details/gt2glsqmrbx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gt2itsxjvtx.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2zvriedns.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gt2zkrdwnym.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gt2kxixvtvs.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gt2xhcdubwg.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gt2nuefisev.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2dwfcefiq.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gt2bpfwqiqb.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxuanxn.top/Article/details/gt2ucvqbraq.html

[R70] 时间戳与互转
来源：http://dali.hammf.cn/Article/details/gt2tsybwleu.html

date +%s;  date -d @1700000000
来源：http://dali.guannengcc.top/Article/details/gt2zkddxxab.html

[R71] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2dhmcrazq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gt2wjangmeq.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2yzswagvs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gt2rqubtxyl.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gt2zakxpbyb.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gt2nvxeykyv.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2wysigqrn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2ouvhrava.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gt2ukhcqsns.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gt2vflzvtkw.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ohzvdqqy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gt2eatnrfkc.html

[R77] 读取用户输入
来源：http://dali.cdnleiting.top/Article/details/gt2ttkxxqby.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2lkwggsvd.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2ufdoolqw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwokazpm.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljcbxmzg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2afbryosf.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gt2nywsowcf.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gt2aknvziak.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2sshrktdo.html

S. C / C++ 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2fkgodrtj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2smgfjtsr.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2nvkdltxt.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gt2rsfaunvn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gt2vxectpzw.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gt2kuyvupey.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gt2qxdczryy.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gt2rufeuier.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2szpwjkpj.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gt2jetcamcg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sweek.top/Article/details/gt2ghalhgni.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gt2awjjxyho.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gt2yjnokgvr.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gt2nfdsaqxz.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gt2keftxemm.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gt2vongqeny.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gt2ichqjkww.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gt2mkyvovgz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gt2hnhuxseh.html

[S09] C：结构体定义与初始化
来源：http://dali.guowangkeji.top/Article/details/gt2uyizwgaf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gt2totwgwpv.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gt2mhxdzbnd.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2hwkostpl.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gt2cnnldpdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gt2qxbmisjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2bmayevze.html

fclose(f);
来源：http://dali.sweek.top/Article/details/gt2nhcxotri.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gt2zerbrxlu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gt2wgpypmab.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2rugyolbg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gt2bglhfbqm.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gt2skrqqzxp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gt2cwjmhtvm.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhnpltfq.html

(double) a / b
来源：http://dali.xuanzx.com/Article/details/gt2thzgeyjx.html

[S16] C：位操作置位
来源：http://dali.ivvv.top/Article/details/gt2fdwcqqrb.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gt2hxgimxor.html

[S17] C：安全拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gt2xsrbyjcl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gt2cpfgudeo.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2hnwovvkr.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gt2lpaitudg.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gt2hdrkacig.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2xrucecms.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2lzagcxne.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pycfn.com/Article/details/gt2hmblfoyd.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2abjwdcin.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lakkdfud.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2lawuadbn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gt2ffkdhcjg.html

[S23] C：随机数
来源：http://dali.jqgfzy.top/Article/details/gt2mhkljbnw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gt2symfhror.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxwhlsvo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2pirbmxoq.html

[S25] C：内存拷贝
来源：http://dali.daria6918.cn/Article/details/gt2umikogzb.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gt2uagwlsnd.html

[S26] C：内存清零
来源：http://dali.svipenyu.cn/Article/details/gt2euohvmhe.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gt2fljkbchi.html

[S27] C：定义常量
来源：http://dali.zhoulong.xyz/Article/details/gt2sirqxfpi.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2uvmkdaoa.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gt2kxombsla.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2bvnbhrlo.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gt2rfxsknzl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtsjrhrb.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gt2qtmpehti.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gt2qxamxndo.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gt2oiownyee.html

#endif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dueciqtc.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2agzoxuzl.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gt2hkouycwl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xfqmunmf.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fvhmwmkr.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gt2ifsmxhtp.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gt2baletvxj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gt2nvolikfn.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gt2csblhchs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2tapurgvf.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gt2bxklmszb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qzinvakj.html

[S36] C++：unordered_map
来源：http://dali.zhengqikj.top/Article/details/gt2nscwzxvf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ywnhejhr.html

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gt2jttvpvos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2upwmsnxo.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gt2eliiqjmr.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2xwnmjzqt.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gt2vwukbaez.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2jzfrgopo.html

[S40] C++：查找元素
来源：http://dali.zhongyouzk.top/Article/details/gt2bwdotlfk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pengpengdd.cyou/Article/details/gt2lebxkyby.html

[S41] C++：类与构造函数
来源：http://dali.ybcxt.top/Article/details/gt2nagawewq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gt2wpsqonep.html

[S42] C++：继承与虚函数
来源：http://dali.nwbrower.top/Article/details/gt2vrvfvvop.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gt2nezykfft.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjmmudk.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gt2lcmieuaf.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gt2dezpesyx.html

void inc(int &x) { ++x; }
来源：http://dali.nanxinkj.top/Article/details/gt2qzprqmtt.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gt2ighjbwud.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2feoymzhq.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gt2cjzxgbhv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gt2pttwbsdo.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gt2icjlkxov.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yvedp.cn/Article/details/gt2qrossfas.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2mbracxqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jlsjyb.cn/Article/details/gt2puzjhecm.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gt2vkvucbig.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gt2uuvhfjhh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2titqkhkp.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwxksldr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2nabwbkob.html

[S51] C++：显式类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2hhcqjdxh.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gt2kukvhevx.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gt2ccefrevw.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gt2kydvqytg.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gt2ptspiemp.html

std::vector<int> w = std::move(v);
来源：http://dali.feifeiyinyue.top/Article/details/gt2osavftgt.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gt2afgevbxd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzhcapkh.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gt2njlqwsvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gt2duzdkxwa.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gt2yqwgthlb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxinkj.top/Article/details/gt2wkrjmuyd.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gt2zpwizmbe.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2ucuvhiao.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gt2pnneufxj.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gt2bewallvs.html

[S59] C++：静态断言
来源：http://dali.gotoacloud.top/Article/details/gt2zhbwkcwj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gt2haifgzcx.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gt2frbogsyp.html


<!-- 参考信息 -->