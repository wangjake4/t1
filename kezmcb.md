代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfmakrg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bmikqwnx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2drbznjoi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdkgqov.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zlswngyq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2efisonkf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbjjset.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2itfuvygp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuymtpz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcbzgni.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwizaml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjybwrn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bhirzqlf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxcsrve.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpygjzyz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbdsmll.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbomyzj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbusbfd.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzefnttz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxterln.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2unytexch.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhzijto.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vybtwehr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhqszqq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2okhkqavc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkdqxhw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwrbppp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2scwubjhx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2adrfkgda.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2hyskfnxw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2efvvhbzj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxktcky.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcfezzg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2kacwyupf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhrkyfw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqrrthz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uanxbrbd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlidvyke.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvuosvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qytaiadq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2obqftlaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnvcgrc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwugsaov.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kbixzdet.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2memvhvgb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2clepjqnb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmlunis.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuljedp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rszjerxm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiortki.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxpsmwd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2atvfxbfd.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqauuwog.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2krroldpd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kslazced.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crazzvsm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfkljow.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oowcrxtt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2natcheco.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhlyqrq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zopnarxu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjqazhp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdgmrqp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2llhntrkd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmwtcmq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tixkyeqd.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfurnfod.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqroargg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqroopu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xibpylmh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ooscxjhv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sorffnfh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmklwpbn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvbiukv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brhiypve.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egqsroes.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuizodp.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzikypf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdughha.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2glkelqks.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvtcxqe.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fszxrbmg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfkfvxz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khsvnocw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eapkgktt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmagmpbc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xalayyms.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vfddbupw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxycglba.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqzqzuy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzluuuiy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2skwxvuke.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqzdycr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdyylna.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nelldtis.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zeebbzim.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njzmkxjx.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gasgudcg.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyugmmqg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyvyjty.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpmncpm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgwlgip.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2iroarhng.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxgjoli.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjymsqn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bozccuuh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxdjuqp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cofqketj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprpfwhi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aimvlohk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phwrfgnk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcftsxk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdkvsnv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zurqxmpt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2arwfnpdm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2krcbnywd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyjhdaw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vswdsebl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaghfhl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lczudbkk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvexthh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wypmrcjj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vltagqks.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlfuwpt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2plnwcadq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jpasrlrt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xjakmdht.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2majzrsym.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qljwnxxa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fedvsdxx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ioacxzfm.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gymctetm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxwohtt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wuymxqdr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2btuhgmmb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbdwlod.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2awjjdmxe.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyligru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2vpomkbyn.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cheptfeg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwqqmrl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vofzobgj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhlojge.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvzoaqs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2egfjcvea.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hjleozch.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2racneuqh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hglairrw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2daiuggfq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzgsfvv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pywusoya.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvcxwba.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkzqixr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oechudab.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiurwik.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2upomhnhs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yevskcub.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbbcmuz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbesieq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xucnthwy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cualabje.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsmneqc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2klljrsvk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2obvbplth.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnpknrj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2czwaljyl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbjouqp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgodqxk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdpbcwb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gllhojpi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbngoom.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxfwhye.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wppbkhfe.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvwttxq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuucdaq.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gyythxkd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzmokcc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nihjcynz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oamhrcja.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjtoffn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzsblli.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqfsbqx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2digbeias.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjfprtd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnrrhlh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvzniys.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpgkewj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfymdqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlavjedi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsqrsbg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2redrawlb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhciwps.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2lwjqjtqh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsogqll.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhuaoyr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acpjgpku.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjsukcl.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvvnmeg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2orfoljel.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hgndpcsw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2jurlgpub.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qqotkgvv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyxffai.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ourwgakl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akyttvsa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvpymer.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zokjopyc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phjftldy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeqydkj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rldddbzj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rznmxztw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wlubmnpd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jetgzasz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoktotl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2esmwimec.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iisnkntr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywitxnlc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2verykcqg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2blajqxig.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zdycwmmv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2taukkonv.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mghpzges.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lccvomaq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vevgrbfe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2mfypssfh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpfddfy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wioymuja.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoozevm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsxwqen.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnswfpb.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklzybgf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifydwqnu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2inrirrbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzusjydn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qswockdv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjfxbax.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2isqfulnh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpdtiek.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubantgwm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2phryaztz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsgjxse.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kouombcr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqyrpfn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdjrkyd.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nupehrux.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyixrrf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfufpone.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcfgadf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhxufxq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2msuutbpe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhrjwbc.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ghotceps.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2naznlxas.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ahimxnfo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zisajxen.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dquzuomt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyosnzsy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lssgvblp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpwpaxc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzdigqc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkikhkha.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtgblat.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktchrweo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuwlkyk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiydsthf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2blyznfwy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2msbespxd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvdvmyc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2prguqxex.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eedqagky.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zejlqcsy.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ztlhisgx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2slkfhuxh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdjlvuc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlkncab.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdemwypm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2irloookz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgskqcop.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqanyic.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aftqtkhx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gizifzxd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnuefto.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfjnuei.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbjwlwn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxkfznl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vknsfxyj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tddidgiz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vayioaat.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2znewsdps.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymksyzkp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2urshlwfq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmrehvh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hddwzsyu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoqiodo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oabtupzs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iffyvqkv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqmcgka.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmszpbak.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpimlqa.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyteomv.html


<!-- 参考信息 -->