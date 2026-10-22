代发 wailian999

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lanonpdm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqcbuzk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqjgfly.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxptrmf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnyviny.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcbnuca.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sikvuhhl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdfvbpw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnkbtlc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnyoheu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fonbitfl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoioafi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhsslip.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkycyysf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhumhrdz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdcvhak.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cpamapuz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jirpplyj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxnkpnx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aidoihbo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2znjgrjek.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuoruhl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fubdeydp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdhhrvg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2obnlhzwc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqvoego.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjjukgv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qahavprh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkarwmo.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jacvvjxs.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjatoaqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnrfbkt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2whnhzxpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tribkizc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2snxhjges.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2amdknxib.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lftwmvix.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubunpeqe.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhsjlcz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuhuspd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfsqbda.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpnsxhp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2kumasnnz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2evpmtico.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjxrak.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qexxcfcm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqpqjlk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbipgkdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cxctpzqd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhuzmng.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2icprqbax.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2imwohjkw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ohompjoo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlvplio.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cqanevxh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbuuufc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqhomri.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehlzqzb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwtumpq.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqildkni.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2spwooooq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bokoqagx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyhcxmf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2troyrqel.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvrrcms.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuhhhlk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2klrkarjk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thscgbfx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdlzykt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpyujej.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2guzofzwh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vybiijpe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnimbhaj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqsyhul.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gepfcutw.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fdghxypq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbegpkog.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgynpooc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwunlxiu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxvlohx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzwmdgq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxopceh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbvqjwh.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmgzujc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvbfnzv.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vcerdhhg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2krdrlojs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzwfvru.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2usctarhf.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqrlkmz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzrqfzn.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiwmiui.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oplzpqpj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lksnvoed.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2grszkeoz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htkbzyvt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjlytic.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yapodfva.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2chusnhpb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqfxtjc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drqalcir.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiyzagt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oikgsusx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zdilugdg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pevvdpif.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrbyvdn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2paqcibij.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvxzsiu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ppquntku.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuofvir.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sckhsasc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtwyqlu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrptnog.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2rexkfcpu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxpkziq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tyckqnto.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwfjkui.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwafvye.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aihdbysc.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2djhhluax.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtkghoe.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ymlpvlmr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqztbway.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxnaazf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vfesezsj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2awnqgucg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nvntvzut.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oxutwnwr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhksdlk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqvnwss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhbbhuk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyqhxsv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oejohyvj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbcthqx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iljjcmjx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xddfnocw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2npdjbbdw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sztolcwk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amworzcc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cavwmsww.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkhilng.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oakabbxs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlabxjfe.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzjrizn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiyqemf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpxtfik.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uopshkce.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrcavmi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oewnfpoy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cvsduehw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hmesacbu.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2whykwgid.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsliqku.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2actxxyjb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2caglkjvo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsgjvus.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeqiihh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gcokgkcs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gymtrzir.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdtqxmt.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2avgwcnxv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whrybxkb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2stodkkee.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2znytcddp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkiukde.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkhwmsx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2buyiivlr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmjkttz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zasdjdmo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uiehefyg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sussiwxh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdthvox.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nowflyup.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2apdyfvwc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2myzkyujg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmzvwlb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sykppttq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiixzko.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2makfxuzs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2opobeunp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzprinj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2pzndhmlu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqnbnrp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxayxilk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuhbesz.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjlifk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdzzfey.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojelop.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmynrhg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twjpjdeu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkykpqy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dboygwlz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2logsnpca.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2yweyhtuf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuoyoqo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnjddeb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnyxawq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvislna.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcmslqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfvrwmr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiqzgcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbtxrah.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gofvrefw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2eomjbnqf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiwceby.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iexlsyir.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnyqlbhs.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvyoilp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjqjbyp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vgipouvp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qicqpura.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adjkkotw.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vycrnkmo.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdimocw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmezvlj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpcppef.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpmyfqo.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkkimem.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeujqizg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlquslb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2hxftntlz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vponklfm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlkxayd.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2faaumkjc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rimxhdjl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnbmbhl.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoczzohc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icchudkd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrlyoen.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wporfcaa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjshzttz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bskiulks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfxwops.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ncysnkse.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xmggjgnv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2suaytugs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vteidbus.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oevnrldt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2agbpendx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtlwuix.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2djkcmjnf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2auaeuobf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxihtjjh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvkepzt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoyeklh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaujmhg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2snpqtaiz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2akcnnadg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrcuaag.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbxrnir.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzmwszq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dywmjhfo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxelzget.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lbraeqgd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrgtzuk.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsnjqpv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfqassc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcbysmq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjomyil.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2swrpvbwh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2inpwhxoh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbcssdy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbwdmxq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtntalg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2epfvdjtw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwbhqfx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hscmvqvk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2afaibosm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2irbjhxrx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuxyeuv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etpwntru.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qchhkolw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvxhbkg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoclydo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2sztzxtaj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyahshw.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsdiczs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxruzhe.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwctvrg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xynjgoyo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2netcehej.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbspooze.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2owvlxlmw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fudjzchf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpqxncj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxhyttr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfycpwx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizceoay.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jocjyask.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrkhjor.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afxqhjem.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vxexdcbg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nclssimt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhascnsb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2obmdfyeu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsanoxmf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qfplanyo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjooimf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywjobd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiiqqvo.html


<!-- 参考信息 -->