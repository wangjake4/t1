代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.gaohongyu789.top/Article/details/gtelooirew.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwipwxwc.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtdovqamnw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtmtijifku.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtunvhoqul.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gtqytlxzhy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtsjqjmghe.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtavlnhuqp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtzbyiemvn.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtjmotfuki.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtciesbzlu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmadpylxd.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gtfxjhvdlm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsopjwnup.html

[R01] shebang 与严格模式
来源：http://dali.zhongyouzk.top/Article/details/gtkhteurjh.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtqndkvmgs.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtqtralkvr.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatrtywqa.html

name="Tom"; echo "$name"
来源：http://dali.bjfxy.top/Article/details/gtesrmhxbg.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtmvbuiyks.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtovekmptf.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gthnhjnxnl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtarlicbob.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtwlnjpnwg.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtdrtuaprf.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtupezhtcs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtfvahrems.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisdyygsm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtximrvtbt.html

[R08] 数值比较
来源：http://dali.aizwys.cn/Article/details/gtatdzcgvz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gtbgavfeii.html

[R09] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gtnqkluxnx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gtadrpxwnc.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtlpolytrr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtgohcywec.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtvqlzxbqw.html

case "$1" in
来源：http://dali.jinqigufen.top/Article/details/gtpossxagv.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtymohjzmz.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtqnwyhise.html

*)     echo "未知命令" ;;
来源：http://dali.guannengcc.top/Article/details/gtfgbdzvgq.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtmpbcyvdv.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gtwuttsuud.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gtjlydwluo.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtefqkuofj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtmeyosiff.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtinramqkd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtaqhqsefw.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtfxpcsoaw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtxtvpcfog.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtkownjhso.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtnnpmhzfr.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gteudefvmy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtsfbukwux.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtzvoglkgy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yanxiufei.cn/Article/details/gtlqhxvyir.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtiewkwaqo.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtmvxmprwc.html

[R20] 关联数组（字典）
来源：http://dali.zhengqikj.top/Article/details/gtbyekbpxe.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gtypsxpkqg.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtpwosxsol.html

echo "${#s}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspocnpui.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtosbinryb.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtutqzxydp.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gtuthtmbvo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtirtyupzl.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtxkgvajgz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtmlpxnnzt.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtfssoyscl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtssabwfse.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtnitdptcz.html

now=$(date +%F); echo "$now"
来源：http://dali.hywenlv.cn/Article/details/gtppiiwazk.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtlghyzreb.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtgswrmnwt.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtygiiegcg.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtmgdgkcyw.html

[R29] 定义函数
来源：http://dali.svipenyu.cn/Article/details/gtqtdzzbbk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgulixzb.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtdaqxlkmu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fzhhl.top/Article/details/gtzvtxakoq.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtyosqaksf.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtvdyfoawd.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtydcnygzg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gtlgtbmsrd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtthmtfjvv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtgekpnrnt.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtnpiyncce.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtuanflkvq.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gthxsyefoa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258.top/Article/details/gtfnbcuqre.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtdtdecyqg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtwfugkixa.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gtdijqzkev.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtvmkcflsq.html

[R38] 管道串联
来源：http://dali.fengsongda.top/Article/details/gtpgouyaki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtdvllqpco.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gthsvfkeuz.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtwhjrbqyi.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtmxktndhv.html

echo "log" >> out.log
来源：http://dali.smart0.xyz/Article/details/gtwlswtfty.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gtkygblpzg.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gthzexhhua.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtsbgthgsq.html

wc -l < a.txt
来源：http://dali.chenzaomai.com/Article/details/gtffzbzewb.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtlaoypdlh.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtfqozmylm.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtyhgglvgz.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtjwliqjdh.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtguemctih.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtksotgfiz.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtnsziaake.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtwikehava.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpghrucgf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtemglhmxv.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtttglenpl.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtutxviokf.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtqxskvjha.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtvgndhzbm.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtukeywzdu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtquwayfwo.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gtmehhcbcf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhengqikj.top/Article/details/gtootaqbxm.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtfmhydjsb.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtzrkqgidz.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtxjqmerzj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtdrmnvefj.html

[R54] 比较两个文件
来源：http://dali.c1oappe.top/Article/details/gtmlluxdus.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtxtnniscp.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtpldkfbne.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtcxiortdn.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtaweshaud.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtagadyebx.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtwewqnizt.html

ssh user@host 'uptime'
来源：http://dali.xylfe.cn/Article/details/gteljlfrlx.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtlkafygyg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtekzlhpcx.html

[R59] 发 POST JSON
来源：http://dali.yvedp.cn/Article/details/gtylbnmiwz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtklzuogkw.html

[R60] 只看 HTTP 状态码
来源：http://dali.ydzc1.top/Article/details/gtsramyxky.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtsejqhdcv.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtsmgdhstd.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtepuvnvwf.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtuwlabzkn.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtdghkyiee.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtrlhemwrm.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgufenzy.top/Article/details/gtuuwamwhw.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtovqfgqdx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtddltnrsn.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gtmxhbedqi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtuenmqruh.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtabwwfagd.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtvzeqflqa.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdpassgp.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtquptxtrc.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtoevcgkji.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gthjmsoewy.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtexfjhfxi.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztohiszt.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtlykrrduk.html

date +%s;  date -d @1700000000
来源：http://dali.birdmap.top/Article/details/gtjoudhyqv.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gthrfwanrq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gturlynpwq.html

[R72] 等待端口就绪
来源：http://dali.sufxvd.cn/Article/details/gtlwdzrrgs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtvcpusyky.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gtiqufxxes.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtcuwuhsdw.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtvvizjthk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gtuzgmbcdq.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtbjozudnv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtblgpkhzl.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggqmmpsc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtkfoyjxox.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtxcidxicp.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtqunkgmnp.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtijzsyjul.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtdftkcbsm.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvdhvrba.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtfetnecyb.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtphntaohp.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gtsvsjkgea.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmfnvppkz.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtcykfcywm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtygluopoy.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtrecqkjkt.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtlrcrtgcw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtghywiwtq.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gtmfaiohrd.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtcxudtfjb.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtriqfucmx.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gtpicodwvg.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtwgvqddap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtibhlusid.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtflkkvkmf.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtvivftjpv.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtnoxfsjsx.html

strcmp(a, b) == 0
来源：http://dali.cashguo.top/Article/details/gttkzrxtdg.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtiyrfkuwp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtyzhznlpj.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gtwbxshjym.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcssycunr.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtublejnci.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gtccoqcsef.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtykbnfsoj.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gtaopdmccp.html

[S11] C：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtqkxbtlzj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxtxjtgz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtcyqpybvc.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtsgjyiduo.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gthpvyocip.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtishbvpqo.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtressqtvs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtsevogrgi.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtxufchyfb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtulequrpz.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtqgrtubao.html

(double) a / b
来源：http://dali.guannengcc.top/Article/details/gtdmuuktnn.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtasrirajx.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtmbyjtweu.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtrnvzhaya.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtuobknibg.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtfkbbzlvs.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtnyjersof.html

[S19] C：快速排序
来源：http://dali.vqdsnc.cn/Article/details/gtgwkpdbzg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtkvbnxeww.html

[S20] C：二分查找
来源：http://dali.cqqwz.cn/Article/details/gtmbzhacaf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgrlafmi.html

[S21] C：字符类别判断
来源：http://dali.xuanzx.com/Article/details/gtblyatogi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkbpfggv.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtcxmgfajl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gtcfrtbinh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gtdldpyyjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtpnrgtkpn.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtbozshsci.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gtahptzubb.html

[S25] C：内存拷贝
来源：http://dali.ybcxt.top/Article/details/gtxevdzrnh.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtmlmuxjjt.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gtzgxwyqrl.html

memset(a, 0, sizeof a);
来源：http://dali.yonumen.top/Article/details/gtcyokojqm.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtcvunzbvg.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtomgemuoi.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtrnumtavd.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyyolrxs.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtkutvmhpv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gtcenjagyb.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gtwvwmkrom.html

#ifndef X_H
来源：http://dali.nanxinkj.top/Article/details/gtalvnskcv.html

#define X_H
来源：http://dali.yueranfly.top/Article/details/gtkbqemzxn.html

#endif
来源：http://dali.svipenyu.cn/Article/details/gtxpefycoh.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gttvqxdsbk.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtgquksyax.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gttjzapunu.html

[S32] C++：字符串
来源：http://dali.aibaodan.cn/Article/details/gtekrudozq.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtofskfnqn.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtbhfbcdcn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtdreresis.html

[S34] C++：遍历 vector
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnycipdol.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtrdthivqn.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtwnlftfzw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtdzuewaks.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwvufoww.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtumnvpvtz.html

[S37] C++：set
来源：http://dali.yonumen.top/Article/details/gtrdwtvdjp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gttzoifddd.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtotalxlqz.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtagugwxfj.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gtgzfkkyhz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtqgihiqsd.html

[S40] C++：查找元素
来源：http://dali.ybcxt.top/Article/details/gtuehwmwpu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtwzohyrmq.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtjcfzcdjb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtvkhbkvua.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gttvytupml.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtmtrhymrn.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gthsbkskwl.html

auto p = std::make_unique<int>(5);
来源：http://dali.guowangkeji.top/Article/details/gtecpiwwgy.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gtiandnbjl.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gteequzwoq.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtiblfouvb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtoqdwdipg.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gtbrsiszlo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtmpiztgul.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtlvgyeeck.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtumyfazmp.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtcefhklrw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtwcxucyxs.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtqvvzpbjf.html

[S49] C++：写文件
来源：http://dali.yongpay.top/Article/details/gtgpvdbwnz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgylxcvud.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtosslrpny.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtbvuvlnmy.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtnafjynfq.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtrionctkg.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtwgjyylgf.html

int size() const noexcept { return n_; }
来源：http://dali.316326.xyz/Article/details/gtwpniinep.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaetkvnm.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtbpicjggc.html

[S54] C++：异常处理
来源：http://dali.chenlongwang.top/Article/details/gtoknwoafu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zycfv.cn/Article/details/gtlkbwcuwy.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtcaybaual.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtrcaqknwz.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrmlawip.html


<!-- 参考信息 -->