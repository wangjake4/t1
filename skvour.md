代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgttgtt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzihizq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2erbgmdpx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmfykzb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeyjwut.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2hznsqelq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2reoxeyxj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cirfxike.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpajhvh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlwkezw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwwfqyc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sxodtyzv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsclmgld.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2fraxgqbf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtmgxhw.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rthsysed.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eehkbvas.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zziplyaa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cimhgglb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2juondfsc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbnkdwj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlzeiuy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbrwkbrz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2klarqsxm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2alagbcuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdsnceg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2outzhfdi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yjavznjv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmufhwq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzecslah.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzzifyi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqfpzky.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xksfttly.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2peukgrgz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcgecsp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyabepuw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxypmtt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwpgckz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoqniqr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzotjwr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdcdoin.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pajstuas.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnqrtza.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2trasgxbw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfzkouy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yitgbnas.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvbezpl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2capbcxbi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2spkmfitf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmhhouf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujuwrxn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hideitgo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzdzzsw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpffyxy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2inclfprc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvnvtjw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwyktfc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkcmnkg.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwlfqpx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcnflsf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ougmpxlf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fivhcrlj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvjmgmz.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2prxtoagw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfsvwix.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2offmzqlz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlakvvg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2thhzgdop.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvioamv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwueqju.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unjvnigq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hetrcdrx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kalunlod.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ycynqvmz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xrinpugn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2asqafrvu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhledyr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnzkrl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvrjabi.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbmfqlw.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xckfphrd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2klblttag.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpvaqye.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjdmpjk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yaozspwh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thiffqsx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyujofs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrdxxtf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzmklgi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jwinjvyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjptrikv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxtesnz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbbwthe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2blpjooup.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjyeulz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxibupu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qixxxlbl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ailkwvch.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwnzupz.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbtrqnk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpppiuvs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2myvviujr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqwoxmh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pttuqnhf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrnaqzv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvavqik.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaitrqj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qppkpxwu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ianfdrdq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdawrejs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtamhjtk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtasfwc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsashadt.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggdrel.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2leanjdpb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gontgnfy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2edbjgtsn.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oclcsxns.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pignsaro.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egmspstn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqotuxe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aupazgsh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzmexjv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sujgrmlu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlrvsqt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2naquiaes.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzdrxgk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdzczfo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2tsosaubh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uydyzast.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yekkxgon.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rojriyoi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkvzqbq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgelxpcd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dmihdlvz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeiypno.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bndujqmf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ooswlbnb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wwymjtgx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gobzwnpo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2onegzrsy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nghwcrky.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkyoezo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtaeord.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2znolraeg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2epiyvver.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyqmjmn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqnbocq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwrrnna.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyktcpf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ovakuang.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fznjwtri.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtjfgn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jalghfez.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsgjsbq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rtheogrh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msgunhuq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrwyxjv.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gnytlbha.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axkncdsf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgubuzc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrunqhd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcxsiti.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fppgfwcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrhfycx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyuatwn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2juuuwodn.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nxommihn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jbltkavd.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psvyawle.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzfsjae.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfxsqnx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tmquoiig.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oiifkgcm.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqeatbl.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vettviit.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfworaz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrdtqzf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgptzmc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2isuusdrq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjmqjyl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkmltwx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rmueagqg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vuvmuang.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2fdihrboa.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oydbgyca.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvuqimh.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xjquubwg.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hxppjjjh.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2njsenakl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmktiuu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jndiglvw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkjunmq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpiofml.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cydwayht.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2epntnzuf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmdpaao.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkdfsqv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrxqwup.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dhusrenx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwoiynn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zxndovrp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2moruiest.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ekulievr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfzvxpd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbiwpll.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhqgqda.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxstfs.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2sccjcpcp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2bupqxmsn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqdlxoy.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fphatgse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuaieww.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evqpotcv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2heocgkhl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgoher.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bmflazha.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vavpsopn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkmiwlk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaajytw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sorhnmgu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zcblpklq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwgjvro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhupptex.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzipmyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqhieou.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojapdpgf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnnyyho.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odhargzu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kijbfqbi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxjwphg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2webmwwmd.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2atuoydgg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2zfawpdlj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2fwemgcvo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2puutyyme.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqucsfnw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hsylbcps.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwtbnfy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxhjqrh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xwixppjb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjtyawu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtxzlij.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxvtzsk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bihgykfr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnxapeh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeaoqet.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lkglpycg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yymoumrx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aphnscim.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dolacuip.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alatizjd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsjjzse.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mototlyy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qynzffws.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgihvfo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwezqfd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbgkdkv.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpexkbp.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2glhyrwyc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyicjdwm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2usnzouag.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vppvsont.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbvztex.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytamarav.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhvscde.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvegoyht.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bkitemqp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khauyctk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lrikdyiy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfevyse.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2llhozxhx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxtjysf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhzehwz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaslzfr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzygkos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uduopmjy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzvliwg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoprdib.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxonbzp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmmclpr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2taveppah.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxbklxq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbvviuq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbsaupe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpewymhz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxtnbse.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbibmuz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hkckxsqy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xdruknax.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuioxqn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djitgion.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2blrygnnq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgjclxa.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2urttfapf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2grvfcaoo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhjlygt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsbaphj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uffhmbvs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyilegez.html


<!-- 参考信息 -->