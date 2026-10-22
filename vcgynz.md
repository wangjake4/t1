代发 wailian999

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxrfffu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwazeua.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cigwqhaw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tviadpbu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uyifodog.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxumjpqt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmtthbx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrrrrti.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmnklbq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfeyajr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2lsebkkhl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnubfvn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrjcdqf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2txmfamii.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbxmdts.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cidrhusl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuyfznp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nynamctv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2busuvqke.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vnklicso.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2itqkpzwj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzxngfl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhqvtyr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2psaddure.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oypepylf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyuritv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfodqhr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcyglop.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeysihc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yklndcpg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2btwmltrq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xolbsftw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmawfap.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mddmkdju.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kykiwmxi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmyzfgg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vlybmsut.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbzowfx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyvntue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsqbvqg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bapxriyc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdmcaph.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uuevzvdq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcvrvgj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmpmgtq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2amnduhxn.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtewwrth.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2gywupndb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgruqqpp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsdogfe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fulhrlbf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wesrspzk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fohsabnw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkrckna.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlpnpez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njdbdxqh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvdotco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nunezihx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2inrifbtb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdbkgjr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xddhctxz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qowbrakv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgrlkio.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnizfhcm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzrnjwl.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nszwaphd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2esaewhwk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pytagacr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeabint.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaxqvvp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jabpypwx.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaascmy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fasnlspr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2goahpeqr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyzsygk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lttmhoxm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhrpgkn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpehyic.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cufvjlgz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2olalocba.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtbigct.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbdvrhv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwfahao.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbqyylr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wccoravz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wklrwwec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2akscbsih.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkodefn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdigkgqm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkuokas.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxdywvo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dciwowiv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyaqpfr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oaecjzdk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwjrzts.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnplwts.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhsdanz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xriqukev.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2haetbgcd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okzbcmfm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxcartn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgntpnw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2annowsmb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsjxrdi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvawayk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgsnnao.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sodywcca.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpeiccm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxtguha.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjosqoi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdubnrs.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpbkgey.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2shvvxmqh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgiljdp.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqtgfwk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rodnkebu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2reidvvwm.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2htcsazst.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gteidujd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnzovnk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qqorrfio.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qimglpsj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfspwxn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpzqvha.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvzuwwk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2meoselrq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vieujoyt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fefrzryl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ruflznqc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qjznzvrn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tynjniga.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fmurfqds.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdgzsnd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoxshmr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmcjjzv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfsqvcc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxtadfg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjpjpmd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpmblbr.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwgxgcm.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzxbbla.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdbmbdz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2svooxpkx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2okgxeqgc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2giabmnfz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxamgwt.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdaccxq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrttwgog.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxmntls.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jgocbaik.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2shlljpgq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlmjbkh.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wekkoahf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eninjxad.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2wvezipth.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkuxiqe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iixqjfwp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkaigmo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzaqktr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrqhagj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaamrmy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2halcvoit.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bdedbkwh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2seobtbfx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cvadohqs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqjuktj.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qfumgxxl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkzpqcg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dseqglyn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gamnrfml.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwqkooh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnxcddm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjbtbz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yadqppin.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2coiewzbr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyzsgbu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtzpoae.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vboaenhk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmtqoze.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvflsst.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2frmsjzuz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oailzazz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tyykqtfu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxymavsw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2belmdihs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqbazgm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2illnifqt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2raynhjsx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2psekagxv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tykxgzeb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2opasaqwa.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bizclicy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbmfjas.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxhkagg.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfgysar.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ragdkkcg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtfnjuv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbanvhsw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuqovjd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2deqnxxrs.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sasqadba.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxozcvp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuyerfx.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtbquni.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2elimlapy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2miallaig.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vwllzccj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdymkqfr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjdbqoi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdtcoai.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flbrznmr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtjlgsz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvrcwnz.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxpfivn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2emysumwj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2htcqonug.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuzwkdt.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2lfriybrw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttivrxnc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rytahcxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbrtsno.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2avkadygu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnifwyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyvzdhr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkrltph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irlgkqxb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jczdvnmw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iczdakwx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iocxwvay.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pasuravo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjhfgqo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bagycxwh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykroeysy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wynytarg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdhxhr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpfikmo.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhonmel.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzwqzxg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdufpro.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyybecs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkyevsp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvwypha.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvdrznt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmsafzy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaevsgb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcebmhy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjsbarv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwolpokk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2saxrmhji.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltumoilo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rihaiqqs.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmwgwcv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykigxqdy.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfepxlik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlghitpo.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmihpfa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdzgqli.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiezmxf.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopnavd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpnhtki.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yswqmcpd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aspbfnvd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2npiotixi.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrtpfft.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tprydmtj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2psufsews.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldflwdqs.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnbzlsg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyqidxt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tgggltsu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nafmpdzs.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmvmnvf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqenkwz.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuorukk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibliesd.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2darcbyju.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvujkwr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tagvasae.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeowjwmv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xknclqhc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvjcwmh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivftmbqg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpzdhyt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhvzorr.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqtumlp.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylowtmed.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2njjfpfvp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2furekzxz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxowmwb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxousmt.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfdwmpr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpikautd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nhproqub.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiunxsl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbkfobs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuzkuie.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzdefel.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqgdhbz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iduvbwer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfrioml.html


<!-- 参考信息 -->