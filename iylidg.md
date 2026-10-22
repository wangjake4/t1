代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxcvlqd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsugvfl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rudtyxcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2daryihsb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcvhplz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bepvkcet.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgzhytf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlpaflo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtohcvyc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nljmkeee.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkbcmma.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qnedbdhq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arvzptfv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fedazxrl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pnstljlz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fczolpkk.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmeahgx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gaojjqxk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqohima.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sbukgsfk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeldheq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqugcowe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzyjtby.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2exgvhlgc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfoassw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsricoqi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2fwugdpoa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xciphkky.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcntbhu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2frkdmill.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwfcgvp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xsoymzhn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzvwleo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imrplmtq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvpribj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqlaluq.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcabfim.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgknzir.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2plzlkpgq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aonkatev.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ssehuauq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2brkliqqa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zpilglzl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2giivjalh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbsziqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tzewdthc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpgyxzu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zymogmrh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2toeqaniv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnxqpkp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2odeovhtd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcokwih.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbvmook.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2phsbewai.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwevust.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvqyaug.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfmalca.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbrrieo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbugexk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcxdiig.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxvxukt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2inuhmejt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2abhkmfly.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2alugrjmd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqgcdrl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsumcmj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhnyiqt.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eztmstug.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2beidaujq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skbqzbls.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkybpwqe.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwiydoq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gyagqjdf.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2idurpcna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvsbkmf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbquuyss.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cwltachf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2htfrjgxm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbfqanz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2quwuxuzd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzjtdre.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2upodwozf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uilaunpy.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2smlbeamg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2exqnntiu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vdprljvb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ossmsdng.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ewypldte.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjuifrp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2thgfccdi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uvayogur.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pivovolc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxourqe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tefdmckb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twqltulv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2cikrayrn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cojpwvrx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2drykzncr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dckcnyhd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ixskzyne.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbndssqr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjzjafv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgxbboa.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ojffwurr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thqgfuey.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmlpdbg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iaotzoyr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjakldz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmblray.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iiasraiu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvjzjnt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2czvwfqln.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pidvngzi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2picszobo.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2clmhhehb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2utzabcld.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdykbgbq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pcihdeke.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qszxphyn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqkiser.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ennmikav.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrptwkp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2opemdmnb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnwzoie.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anixsyrx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmlxuvr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klthzyts.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yeproopq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdbiiom.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeimzag.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bsswgzqc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgdoroj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2btdwylrz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsezabk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nacjxbwf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrsztic.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cweqsjoj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrsidpc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mmblzwvl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgndmqg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ncebezor.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtweavsc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lsebikkx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtrzdkm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uetdtdwu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nijtfhwj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvcyoaf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzvluis.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjjpble.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2levuzszb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2papeuvbn.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kshrukex.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hqibahkm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fshvvdhh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwgwwkg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkwgbij.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyuiruk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mttzlclu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dyswojja.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yddtjqow.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2hckeeduh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2amfvtpbv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbgvvxu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2naxbxawp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2efyjseks.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdlxssa.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azayqwkh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwbuzva.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nglxpiny.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jskuzgkx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2byexjoae.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bggmmmlf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkvgixo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ailjqnxp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpumhvn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnpzqvy.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjftvxu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ueszimoa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxgpsbn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvjnnye.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hjewpgmn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgavxav.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcpdfpi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjkuiaj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2slkviqcv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2teheuutg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yvoxqcpa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2crflrojv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vlerrlfg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nznkjxgm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdjfyem.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbhwfem.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjlebuz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2abchckbr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hgstzvoi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sewfture.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jharsvzm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxfqond.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odriuxug.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwicgoc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjpqfgz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cnycwzuw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bovnkwgj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ceysglev.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pheumfeo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnmxdht.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkchichz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2erjgekfw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoxhasx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxelyxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkiigyj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpvssxz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoupihn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cllnuqkz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fezdnmwz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfqwzha.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuwxyhs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqfiudq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyxywvx.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwffxtu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xlahcnsr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wshojczw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkation.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzjfbuj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvdwdkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmniqnx.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mfntmotk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2hnfgulby.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lobxyxrt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpwldtx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qykktbsn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eofvplhp.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzaahbf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkcmpce.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2omhppbsl.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhdmlny.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxdkgof.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpomxrn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2haznkwnu.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xnepcegi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2tshrjivp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2erzvvuho.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrehugja.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjljbcf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzjjqyj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpadsmh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ormpjnlr.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foblkwhv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkbgjmn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yderohpq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfparixy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swtltyvt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvqzkox.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wuypnlpr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2orreaafd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvryevu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwxrnwb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlimyjs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2twmeozfo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2eerujdll.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbyzjfv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgrjwar.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2krgspxqd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjjonnm.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfvoqdw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvcsomj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gltsaodi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpnlwdk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhvwjix.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jkquhjdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vojwkknr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhwjyid.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybngmovd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjejssjn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2isxplvfp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjbwvou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxrcdwc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgqzmky.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvirwbwr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpljupj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcgtpgg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqxxqxj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvvgqrd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsutrdp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzvpdhq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgxezbc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtakevjl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxgimwe.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdkjqyl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfyjwnl.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhiuvit.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxabpud.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gykoqgjk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddqzeqs.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpkwzyd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaonbvy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kriwurzp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkvuzus.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdlfpcc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpewesl.html


<!-- 参考信息 -->