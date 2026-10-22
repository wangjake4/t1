代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmzwojki.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gt2ivgpxopd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gt2smmszwbo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckyinqbn.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gt2xziiwhze.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jxwcxcll.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gt2ixjnzuql.html

#!/usr/bin/env bash
来源：http://dali.fengsongda.top/Article/details/gt2svnnpmmg.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gt2ieddwzid.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gt2xxvebkkm.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2rscpkzmy.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2sawyneep.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2aiwvdorl.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2khmysvkh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2ygkettqk.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2murefniq.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2zvifdyab.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gt2jhjmhrqx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gt2zpaizfsj.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2dgkdqhek.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkpzpxov.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gt2ptttwlvl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gt2qzgioroq.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2mriakuur.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gt2bcuirfwq.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gt2meylwvuw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gt2kzeqrfxw.html

[R11] case 多分支
来源：http://dali.9152youxi.cn/Article/details/gt2hagwlpdb.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gt2rwmyvsgj.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gt2qaezlmlo.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2xlctjfef.html

*)     echo "未知命令" ;;
来源：http://dali.tanke756.top/Article/details/gt2pfyhcllm.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gt2ietmuufs.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gt2gwsmfccs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2nywvsyam.html

[R13] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2frnptmxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2rdpamate.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2ccpjnsvm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2tdbkdumq.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gt2cqlqmoej.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gt2ghmvnkpv.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2tijlxcwz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gt2hunbfcks.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gt2linjtbga.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dashuyun.cn/Article/details/gt2ltmmzvkx.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2kabsyxhg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gt2rklwlhxw.html

[R19] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jszwkvmf.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2kjqetnue.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gt2vrlrqlay.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gt2vklupnvh.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjaddbjx.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccrrmbnc.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2sqrugeut.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2cwxdrsiy.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gt2cjsxsjul.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2houkxlsr.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2bqsipvkf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gt2jfmfzkiw.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gt2hxrdcyng.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gt2qqtryiav.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gt2uwpwhuoc.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gt2bwkjsahd.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2srknuvgk.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gt2fnfvmujw.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gt2cgabzygt.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gt2bptzbxcf.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gt2oawvglst.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jlsjyb.cn/Article/details/gt2uqlahmqx.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gt2pdarjxrk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gt2guhfwvsk.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2hrhsuunl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gt2avnbwasf.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gt2ghsfbfsp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gt2zlpaxikn.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gt2amrbfbnn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gt2evpjrwlw.html

[R34] 退出时清理
来源：http://dali.yuxming.cn/Article/details/gt2kdxbwaiz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2vmfbzwwd.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gt2bvldopbw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gt2lsgslxma.html

[R36] 并发执行多个任务
来源：http://dali.tanke756.top/Article/details/gt2pkxmeqke.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2mcjlftiu.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gt2wmmivgqe.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2ptmuflnx.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gt2djeqtwux.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zdqjudy.top/Article/details/gt2yrxkxasq.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gt2scbcvxey.html

cmd > out.log 2>&1
来源：http://dali.xinyue.icu/Article/details/gt2iiqbmczz.html

[R40] 追加写日志
来源：http://dali.cqqwz.cn/Article/details/gt2wkvdwyuf.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gt2tzncxorh.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gt2uipippnp.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gt2jqnvriys.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gt2ludqmgne.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gt2iidnbqvz.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gt2wcwvqnql.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gt2oqhetimh.html

[R44] 按修改时间查找
来源：http://dali.xziqi.cn/Article/details/gt2ueieafdu.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gt2touxpfca.html

[R45] 批量删除
来源：http://dali.yj20258888.top/Article/details/gt2nrienvsl.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gt2pnfnzsoi.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gt2zpwedoex.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gt2psitpiwz.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gt2yqcmiwbm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srjmjsls.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwwrjubx.html

awk '{print $1, $3}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2clhuguri.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gt2aseqsgce.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gt2rtdtyqhe.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gt2xmuqqchg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gt2znjggwjb.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2biuwvzqh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcfhtfzm.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjmklesa.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2ahtbwhgo.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gt2zarwvuzq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2guxsymjb.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gt2eukcotbj.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gt2lguymbty.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gt2lqddxjeq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gt2hwchuaxp.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gt2ymltulqh.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gt2owuqlbfd.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2nquddxfo.html

ssh user@host 'uptime'
来源：http://dali.wangdashe.top/Article/details/gt2rrfcwevq.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gt2fzpltskf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gt2kwxrfsdl.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2drzoxhhc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwauyffm.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2hmdpokjf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gt2fkuylbvo.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gt2rczuazfx.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2pflktnfu.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gt2hsmjnjst.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gt2vxlmepdr.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gt2frgmtgcb.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifwhkknb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdpfrub.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gt2xwopduhf.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gt2giegztim.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gt2tquzktoc.html

[R66] 定时任务
来源：http://dali.nwbrower.top/Article/details/gt2niyiokvj.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gt2dhtceoyn.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gt2cfestjis.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gt2ndgdsdme.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gt2vtsqfofj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gt2vdvroulp.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gt2gspxrkeq.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gt2uqhjwzic.html

[R70] 时间戳与互转
来源：http://dali.yvedp.cn/Article/details/gt2udzbcmbz.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2rkhwuhcx.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2tfliqjlx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2nqjnawxb.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gt2uagessky.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2ekzkraag.html

[R73] 分割大日志
来源：http://dali.ybcxt.top/Article/details/gt2gcuxuowb.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gt2kvagyjyk.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gt2ifncpuxu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.haohaochexian.top/Article/details/gt2hflyqzoq.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxhxskou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yanxiufei.cn/Article/details/gt2hviviiew.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gt2mekcxzhh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2qhsjaqbk.html

[R77] 读取用户输入
来源：http://dali.zhengqikj.top/Article/details/gt2itpjpxii.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gt2xvhuicyz.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2zgzrbpvf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gt2zzgjtknk.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gt2zajgduuv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gt2fyobvcdc.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndbtpafd.html

time ./run.sh
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrggblfp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2eytlumgz.html

S. C / C++ 专题
来源：http://dali.yj20258888.top/Article/details/gt2ucrrjbel.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zgoqmxux.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2dmkmnvsm.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gt2yotspgar.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isadtbir.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2euvxnafu.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gt2ytsromhm.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gt2rqyhmrvk.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iegpawuo.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gt2hsfhdxck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.iojbl.cn/Article/details/gt2kbetdttt.html

[S05] C：字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2vcaxgiqg.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2phemxwtq.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2xvncphod.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gt2bmgshedr.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2zxfqvsah.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gt2frhckspg.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gt2tpbhaozk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gt2xjaeuiqi.html

[S09] C：结构体定义与初始化
来源：http://dali.dashuyun.cn/Article/details/gt2rxieqrmo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.birdmap.top/Article/details/gt2dhdewxhb.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2noeidlph.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gt2atfjozvb.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2rjbuekbs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dshdtpyj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gt2apktchfo.html

fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gt2gissnyod.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2xbrhkatz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gt2vbobyhey.html

[S13] C：宏定义
来源：http://dali.tianlin.xyz/Article/details/gt2jtujyehz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2dykwtpmr.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gt2mcmbskvj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gt2npkgksyi.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2rrpvklar.html

(double) a / b
来源：http://dali.pycfn.com/Article/details/gt2auykaiul.html

[S16] C：位操作置位
来源：http://dali.smart0.xyz/Article/details/gt2yaeaitwd.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkmirpwr.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shknvnkg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gt2ztrgrnpv.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gt2sddqzbdt.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gt2dzmzloof.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqcvayml.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2myyyyftz.html

[S20] C：二分查找
来源：http://dali.ppjwa.cn/Article/details/gt2vzageqhx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2hygpynxu.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gt2bxcckzsg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2mgzfaqmp.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2cjbgvnnj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gt2gahgpyly.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gt2qpmhxnlb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hfpthk.cn/Article/details/gt2qexxwzhm.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gt2evgxoizb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gt2rgszrset.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gt2qqrapkif.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gt2enqhaujy.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gt2nvziyslp.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2pjyywwcg.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txggxkca.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gt2nokusgny.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gt2rezlbzhz.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2voowqdfi.html

[S29] C：变参函数
来源：http://dali.redwolf501.top/Article/details/gt2bzyjtjgn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gt2dnorokbl.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrvoagjb.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gt2wpaeadew.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gt2zeeovqjt.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gt2qxcrmrjq.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2wodbmgdl.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gt2ejotfpct.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenzaomai.com/Article/details/gt2aeumxlll.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gt2fndqebxz.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gt2siaqvezs.html

[S33] C++：vector 增删
来源：http://dali.vqdsnc.cn/Article/details/gt2npfzqmod.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gt2zkysxzdi.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gt2soaptmmp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gt2vobezhoz.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gt2qptmiirm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2rbxqhubv.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2lwcahqfq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2gisfgrgv.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gt2qgstyncc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gt2swrbyedf.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2hqsocbrt.html

std::sort(v.begin(), v.end());
来源：http://dali.guowangkeji.top/Article/details/gt2opocfecf.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gt2nmnieowv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gt2muraucga.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2zauhwohj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gt2psmxhzoi.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2xlczfnrk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2potpqqrm.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gt2jbfecmbt.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxuanxn.top/Article/details/gt2lgysrnvd.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gt2ihjvxlxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gt2fbjnzrch.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gt2pcuvzrym.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gt2jgprkixt.html

[S45] C++：lambda
来源：http://dali.jlsjyb.cn/Article/details/gt2docpxtfp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gt2imfbwjco.html

[S46] C++：函数模板
来源：http://dali.fzhhl.top/Article/details/gt2paoljqch.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gt2bsdnquhi.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gt2zqiiuqaw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gt2krrimxwx.html

[S48] C++：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2hdewfiwv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gt2tytvxrwo.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gt2enquorfs.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gt2nxyibqah.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gt2dtyyxxvj.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gt2jqmftnrx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2uomjjgwd.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gt2xyarchjt.html

static_cast<double>(a) / b
来源：http://dali.hfpthk.cn/Article/details/gt2gslpylra.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gt2qrxwalia.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2mmothmvd.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gt2egznsoip.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gt2ruvbexft.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gt2ykpxddmf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzvgpjsf.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gt2axttigjf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gt2kqsechhd.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gt2cufrimte.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gt2fdbpcgyl.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gt2yhadqoel.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2eujfpnkc.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gt2graizyjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2rkvshlsn.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gt2milmtgln.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gt2bxirafyh.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gt2vecktpec.html


<!-- 参考信息 -->