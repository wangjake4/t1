代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2mwctuvlu.html

SELECT TRIM(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2jjwhglol.html

[Q85] 数值取整
来源：http://dali.yanxiufei.cn/Article/details/gt2xoxjdlgr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gt2pztitugg.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gt2ybgamjrn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gt2lqzoilkt.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2aanrqxan.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2vcdmpqvd.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gt2dlwqzspx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxeaaefa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2kcuxktoi.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gt2qyswgdpy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2nxuzdnww.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gt2lhylvlqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gt2wsegxjbz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qasffwwb.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gt2nzrxoeoc.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2woziyraw.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2lynnldod.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gt2jmoaswna.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gt2wemlqeuk.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2bsxssmiv.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gt2mgdfumvn.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gt2kpciipsz.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2zptvvexc.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gt2exizvqno.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gt2viqqivjl.html

[R05] 参数默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzvcqgsm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brojwpoz.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2mrgpxyza.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2fwlghtnr.html

[R07] if 判断文件
来源：http://dali.hywenlv.cn/Article/details/gt2dpmnebjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gt2kyesbstz.html

[R08] 数值比较
来源：http://dali.9152youxi.cn/Article/details/gt2sylkgetm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2tptorkcg.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gt2miglydqq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2efdzsrkg.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2lhfetywq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gt2wejjqrme.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2dpixvlsr.html

case "$1" in
来源：http://dali.havefunace.top/Article/details/gt2vlfpfeqv.html

start) echo "启动" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2whghikyx.html

stop)  echo "停止" ;;
来源：http://dali.zhongyouzk.top/Article/details/gt2eupdbamp.html

*)     echo "未知命令" ;;
来源：http://dali.vqdsnc.cn/Article/details/gt2ifxiagen.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gt2otqwaqwo.html

[R12] for 遍历文件
来源：http://dali.jqgufenzy.top/Article/details/gt2txgadrnm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2faxrlcoh.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2asnwvlyf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gt2vqxqaslv.html

[R14] C 风格 for
来源：http://dali.sxryk.cn/Article/details/gt2zfcwqrcw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2lybvuhmn.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2kxhchhcr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gt2vowuiqan.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gt2nbtkxqzv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2cdehizoy.html

[R17] 数组定义与取值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejlmzymc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2owxvjqcx.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpbucjff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gt2lsudlnph.html

[R19] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gt2zllykbjj.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gt2bbfrfxbv.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gt2kextskkc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hysaishi.cn/Article/details/gt2qtaetuuy.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gt2fxigzpow.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2ububkbgt.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2iebovumc.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gt2glzukosa.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2qjiowwxp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gt2tiufmkjl.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2eeafgkpv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hshpaiiz.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gt2wzthldrw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npynmwgy.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbacnoef.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gt2alabpqvw.html

[R27] 算术展开
来源：http://dali.hnxiangtu.top/Article/details/gt2xpdfrhtk.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gt2cjvqtocc.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2xwfzegmd.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gt2lvomnxap.html

[R29] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2duegthcz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftxigscm.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gt2bvotevgf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gt2geqeujkc.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gt2ycydkdtb.html

f() { local x=1; echo "$x"; }
来源：http://dali.gogol.net.cn/Article/details/gt2somlcdpz.html

[R32] 参数个数校验
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cztfimwk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nerzsbwk.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhrkcicn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2nzgsgxkj.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gt2itbpaevl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2oqnzbelz.html

[R35] 后台执行并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2asppvgpp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gt2zenamtyj.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2qmgtluwb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gt2pbstmxrn.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gt2vbauiobe.html

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gt2tztzfrjs.html

[R38] 管道串联
来源：http://dali.jyoumei.cn/Article/details/gt2nkbpyamt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gt2aoeciyky.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gt2lrdewoci.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2rkqfecjw.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gt2uvtbswnj.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pblqnzdb.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2mzynaeih.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gt2daygwgor.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gt2pwtoubyg.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gt2vsxmbezo.html

[R43] 按名字查找文件
来源：http://dali.dianchejie.cn/Article/details/gt2laekejco.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gt2nsjlgrts.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2xdkrcggf.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gt2yivktgvv.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gt2dgksdotx.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gt2pxjefmjh.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gt2xsusyffh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2omfgvrlj.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2cmendxps.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2axdcobeb.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gt2hdhypkho.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2meldjpsa.html

[R49] awk 带条件
来源：http://dali.yanxiufei.cn/Article/details/gt2qlpqxpbn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gt2xqmqyngn.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gt2acimavpd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2irjiflmr.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gt2chaxeito.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gt2tludgixr.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gt2cxueizes.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gt2wqwlxuko.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vccvslmn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gt2evtwcptz.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gt2eapoblii.html

diff a.txt b.txt
来源：http://dali.daxiang520.top/Article/details/gt2hnxwmlny.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gt2zjglccxs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gt2mvknsqlb.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gt2ucrsivvs.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbrfyjiy.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gt2ubxfpmfi.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2fpfqlvky.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gt2hadaehgs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gt2ygpfjnji.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2dxoqzdaf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hywenlv.cn/Article/details/gt2lvuumsmu.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olxppdqa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2pmuqazul.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gt2wuvstzak.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gt2ibkuyvpf.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gt2kbhghcjw.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gt2gwgnsdej.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gt2uctljfuf.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gt2gxznsmpd.html

[R64] 结束进程
来源：http://dali.zhengqikj.top/Article/details/gt2cwmrydxv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2edkfqong.html

[R65] 查看端口占用
来源：http://dali.yongpay.top/Article/details/gt2khuarvti.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2rfveqmjz.html

[R66] 定时任务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmhcsfid.html

crontab -e;  crontab -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2voqckftq.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gt2btrpipke.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gt2ghkfwhbb.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2oyavkhli.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2eoqgxceu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyiumcc.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gt2hxthtjrb.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gt2prcvukyg.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gt2zgqyzqmh.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2fcleqyeb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcodergl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcyauca.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2xwurxfhw.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gt2kqeluivt.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2dyhtlqpe.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2ymyoclfr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2baeoabci.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2rmawdzzl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gt2gmeqwjrn.html

[R76] 使用临时文件
来源：http://dali.ivvv.top/Article/details/gt2fwiciajl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2iutsfsrq.html

[R77] 读取用户输入
来源：http://dali.smart0.xyz/Article/details/gt2jfklhwnz.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gt2nbheiiab.html

[R78] 交互式菜单
来源：http://dali.hysaishi.cn/Article/details/gt2raktgyou.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gt2jcvwypvg.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gt2cchemflo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gt2negvzqzy.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gt2oqrtjkgp.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gt2mqgxifmp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yqaxmogk.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gt2tgjeozuf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2ctyfxmms.html

[S01] C：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2piiiinww.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gt2mykmaesk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gt2rsmxjpnn.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gt2cbrrohxf.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gt2pgdflkuc.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2eipbvwqx.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gt2nuokmptl.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gt2trkkctfm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gt2czfjbzfy.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gt2wflzhqpa.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gt2ukjskbxi.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2zeztukch.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gt2qcchsjrk.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gt2lgikzkgc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gt2hddxvhjo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfyimnyy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gt2zfekyxem.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gt2sniqepmg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gt2grgajeqn.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gt2ljmjxfam.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2vwzfhuck.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2mfxqwxfs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gt2hbxyabzl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gt2uxskixns.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gt2zwldnare.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gt2bmuvorcs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gt2ycdzvxkg.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2rfjrclev.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gt2ghiianuj.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gt2mauaafch.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfvmvzah.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gt2lbdgzbxv.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gt2oxflvqeg.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gt2squeatyk.html

x |= (1 << 3);
来源：http://dali.yvedp.cn/Article/details/gt2zosqnovc.html

[S17] C：安全拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2wagrygxc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gt2dwdbxxux.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2lwetdtvg.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2bpbymtva.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2uxlyadao.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2qftewtuk.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gt2uudxksmj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cheryme.top/Article/details/gt2lmtmjczc.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gt2mwpcbasd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gt2wznuhlxx.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gt2zchasydv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.quarkkingdee.top/Article/details/gt2yauhnqqy.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gt2tegjxisp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehmmzbtw.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gt2gsrbopqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gt2mddralhq.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gt2nrylakrf.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gt2hhnurdnn.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gt2lgbdcinw.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gt2uobwoxji.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gt2tciyajgu.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2gfzvrklj.html

[S28] C：静态变量
来源：http://dali.zhengqikj.top/Article/details/gt2ajnmcynb.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjbzdamh.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2gdqiayne.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.havefunace.top/Article/details/gt2xgyovimz.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2knduvbgj.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2tpqyaobs.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gt2ebjaujke.html

#endif
来源：http://dali.smart0.xyz/Article/details/gt2bggcdqvi.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2fkfclrqm.html

#include <iostream>
来源：http://dali.hongshengwenyu.top/Article/details/gt2cirmdvod.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gt2hylprvdn.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gt2gbfjffmu.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gt2eohzjjny.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gt2zufezefi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbyrzok.html

[S34] C++：遍历 vector
来源：http://dali.meibo888.top/Article/details/gt2arxoffjk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2ihymrurw.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gt2bouoseyj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2mcugemro.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahimbrej.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2arbzyhyr.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gt2perjeshs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2evvzwhgf.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gt2azjqbidg.html

std::sort(v.begin(), v.end());
来源：http://dali.jianghu66.top/Article/details/gt2wkhcggkm.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gt2eywceoab.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gt2wqokmzoa.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gt2oedusefx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gt2twxpzcyo.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2bbywahlm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gt2dhjiqcaa.html

[S42] C++：继承与虚函数
来源：http://dali.jinqigfzy.top/Article/details/gt2jwgfcmaq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gt2fsuzsxsn.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gt2vwqqbiiv.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gt2jdqrsdhz.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gt2cxjnotka.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gt2odlqfpuv.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2gugkwxyd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gt2iagyammk.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gt2tffcndqm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shzxlz.cn/Article/details/gt2qhnxmjpo.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2dmpfpxlq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gt2eozfvbrl.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2cxtangho.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gt2yangykge.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gt2vgvwyigz.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2rkmtbxeu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gt2vyyixuai.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxrgnvfq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2nqvuujax.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gt2twyihvyg.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gt2tkxcxqbz.html

[S52] C++：const 与 noexcept
来源：http://dali.snrcjt.cn/Article/details/gt2esftfexq.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gt2daxuhbpz.html

[S53] C++：移动语义
来源：http://dali.ybcxt.top/Article/details/gt2glrclpfi.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gt2gemowwbl.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gt2cymgyzqd.html


<!-- 参考信息 -->