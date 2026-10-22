代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbihsss.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwxsjmu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrqbzwb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oijrkxgq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshlwrhk.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvojzsi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lryirkkw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvfevkz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpbqvwk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2skwfczqt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmiurff.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2izgbdoha.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmorjra.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrsfqml.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnjevnp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxkhgrr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmmftfe.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2voedbizy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvehexvt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmntaeu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgjlcqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2lybkmicw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2okuwyxrs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhquyuz.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyhxxap.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kjilfeau.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2henjwtjk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyrfvfq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqchtao.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqqsqpe.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvdzfxh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fphuoqai.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rupyxysm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2larkdmvm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmpowge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhixzgx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2utuyytaw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqwvuoe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xicytqib.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfadlvo.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiqqjgy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyaixhj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cykobngj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfxhgnp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoeomio.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2miiewdep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nutfvocx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aerecqjr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ozedmmoh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqobjso.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnvjzon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anthdqya.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eznagliw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yynccitm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xptakkan.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2seaerdxq.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2osvtjrki.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yqijnfix.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsqwhzz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tykufsex.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfjvhck.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwblrhzv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvvukhl.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lujquhpn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbvuild.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrnxstr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkavfcm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouednatd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oafysmie.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbpwwnz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dehrbuuu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2phkvduoe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzzjapr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nckfwdhs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ugotujxx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuyjwvy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfreegb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bypeqdie.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzxlrds.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmftvwk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jgealpsv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrlzvfo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inykrynw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmlbndo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zdppzthn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tudzxsci.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2miwetetq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2updmtltr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jezumjrk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2koxvtbaq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ihonhkqf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbemtuc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2smqjidie.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2weezhwgk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjrwbgv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhshdtc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apyghvlv.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwwhdon.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdabglp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gsykiafv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjcfmsw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtagaglb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2puacyrkv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ojveukih.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xwisrkbj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pisdttgv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2slpedkpx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gdifdpot.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrywhrm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnchbjf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2agmkybfc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wvowamkb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaczwer.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2huywhlcz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jemewrpa.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lutcprmo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rngwelci.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2catgqgnd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzgxpuz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsqndpz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wumtunpi.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jszdhfpu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hucefjiw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpubjhk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmkjmoa.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpbrrwu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dhovuioj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtuoqza.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2osbshtbb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpocpns.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qffkincw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npywtvmm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uufxesac.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2luxauavw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbskopb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfmbizo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pwifuaso.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaujkfz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bfncukze.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwkeseh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfobepj.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2skfypfhw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wacujyma.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyruisy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrpbvdz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2culifazw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqoskgf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kasanazg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvjbxzx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbpzgzs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2exkciuja.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szphizbv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzlgeco.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkoitmb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tamsdobr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwccqxe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvbjgwp.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dccixeqy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fttmvxtb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwrvxeh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfewlxe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxegtvi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vahxuefn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2eravmrtm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2teltiidx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngthezry.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enclynuk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2smhuhujm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkrivms.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fojjgunl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mezsubmx.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pilbrgrc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiphkfl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcitsnlf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzfpcic.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tghkuatq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmzskxt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxlhlq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jmivolwo.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bfewbfnc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fyspygep.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2murpcxmf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2cskjfadj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlnexhq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hoemrrxj.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpkxmyc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiensfvj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmikzpp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eqopinmk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcslcla.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrxfssd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jetjbteb.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmplhci.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2fmixikxo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwsoeke.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oqojricc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2vxufbdue.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdosrls.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2etzqaisz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wweezzxu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeehotlw.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcztnik.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgwzmjl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yxamgndb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2norqiull.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhpkhvi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnevmpcq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdgcfjx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wepldzrh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcwzbra.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hueugjdn.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxvzzgn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tncsnljp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoqpkdc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnpcrjg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgidxpi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbphlvqo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2depwvzzt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhqgtnn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwlhhq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zavuixeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzwfrya.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cycdoevw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgkrgfz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evqlitjg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ppijkrho.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqerlgu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbqpiyez.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssswmbim.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sodduqcm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2hglvdbff.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2stgyrhbk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cusylbov.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dajydmpb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxjlreh.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmhokdi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyfzeev.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2sgueoots.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2shdthqbh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcryuiv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2agdfluzl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuokzes.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pipogpyh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfqovse.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bypmjwlo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoacbmq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoblomz.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xalwcgoy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jatooiyi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvkoryh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsvqehu.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdgefeh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2efkjpvly.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwqlpbt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmtippg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2giynadub.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaveyrht.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2awnfzrqj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxirvteq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oseuloaz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxjqkvy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxvwkma.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pholrxmh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xmllmiqn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyezzff.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrhhhih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexvzfw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ayicmzqw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bipqhfcz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnjkcvc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrkwqfn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxencob.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yipnlnzq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbvuhoe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2laxtlnpg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2umvivikq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yodwlvgu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdczpsg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiogdpc.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwiftee.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbtfmcm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhgdbdl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2smnwtdey.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lhblaqpw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2psswevox.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sahuetaa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmqkjdo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkhvyhr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbbpkkp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cspzknic.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqdannk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbjvagj.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vslmxwzq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gegvpsgi.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nzutogdh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhvrudn.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2asfafjiq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdwchsh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2opoouovd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euqodpiy.html


<!-- 参考信息 -->