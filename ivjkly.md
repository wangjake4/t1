代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlldihy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdkcws.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzvfppn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaokniw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hubiphoh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwfqgaj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dimlctho.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2joaayunm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfyjocg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgonrvn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gznlvjgb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eohiwpjc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbkcphe.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnyqdjp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyqwztj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kyinqukr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopcemkw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ibngfgti.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdolvyu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzyskyq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxwporr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmgdscs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2seagxuil.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdcauj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2nivjkqqf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhltstz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eryozbfu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lijlohun.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpolokk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbazflk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdlkkta.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2habdezfg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rgebsavo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2szwoneqj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfaermv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbmjrdm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxcrxzw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuipektz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2addugsuk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfvfrgo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyouomx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxagrieh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vibvketc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cevrhknb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ensfaxdc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2covvrdpa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nawautcl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyeidxh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bigufbip.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pupgeqnd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kumtfzqb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2teljomem.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvjjkax.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aaucvrqm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwjwvjn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxrzysb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lakpfurn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2catokass.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmnukms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsijnfn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhmxzbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqigorjw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyciqxa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfeqwho.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qisnsodq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ceziafre.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hezgcucu.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vesmmxun.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnbfrtr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgoyzzp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlltkug.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrdptgq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2paxyedyd.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhwnlqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfkqhdp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juramxry.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hevrcmgg.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hocuzogj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ethpteco.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrixdiw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdgcoid.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vwytznfn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrxokil.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2boccdpik.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtcjave.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiqokoo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdbygon.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2atquwlkf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkmrvdq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxvqvea.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vnckuyqz.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgsupes.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2namzqnap.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2idtbnflq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjflcyl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwdplgx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qutaubjs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqbncbz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2agqizuxm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzgvqib.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djqmgbys.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbetwlks.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmzzkgf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgwtrlj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdjqktc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwunmdeq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vacnqooq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmknflxu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfuskjr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxmqzsv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tszeeeds.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gwznlplq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksijshpn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwdjnmo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqxuadw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vupiwuxt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2akvekmud.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2otduiqji.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2uebcsnsj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lapbpwfe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2aghqpxtq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lerbwbzv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qeawojkc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2givmlaqb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acsungmh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sswyrnwv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooigtcqd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acxkutqz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djajiaca.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpihzjh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krwnssjs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wixiwuew.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnvltit.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwaycbj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bkptfkcx.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2alrhaish.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfqgcpx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uainxhdc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2suppeafj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdxeozb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxyxejx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjwwegi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mhajhoyy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdpyjwp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbbjtkh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwomprp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yayiqiyq.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxfyxbs.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsuzxsw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsuapdi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmmyylg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akkqzssi.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyeycfc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdurlhl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkdsikd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2thjrnnpt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2faxiqmdj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzceiho.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2phdnukxp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yzibudpw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czqhghtd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbvtxmb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mscvrdjs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdndnbpl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iefacbfz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pxafelsq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpikvdf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2abjvtdua.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2irnlttpz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsoqjxh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2znnodjfy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2icqmttgu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hpapfydh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xehtljew.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hexhxnfh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fhixwhwd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfdctd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsknnuu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2efcvopbp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jegistmw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbjriix.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwpxpuh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2iduqzzmk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwhxjjl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhmibec.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cqphgcul.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2owwhutyk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjybohr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwdfzu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moesimla.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2xiupxdhq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrjzgic.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzvsqml.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tuviezbj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2savhzurw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhdgcym.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pufeieyz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzhirma.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdpzfsi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqyqtxy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfmsmfr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmhmscs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rydwzvgi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2igdirnow.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2aefvsimv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yitgbjsn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ysczgdej.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2acqxouhf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhufmph.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfeplfd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjrolsf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdykcyk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2phwyfokw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnyynum.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhqgppa.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqwztxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbztsuo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfgfizz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gegabtot.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjlskai.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdyoki.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2grimofnq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsebcrt.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kaltoeaz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzhuirv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkxmaar.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeuhrnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzgjdal.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2odvpyrgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkjgvjs.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbsqdak.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkgjvmb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tovkaopw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvdzrch.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcvlnir.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmmagfx.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2scxstftv.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwupija.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgnwfmi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcuibat.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxzgwve.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdlqvrh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2csqzhath.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mnazeqnh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpdamkz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2murcfuqn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcibunks.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2abvhporv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjrlemd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbvdyow.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwvebur.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaueicl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2khijjwhi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmlgudj.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vukuwbva.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzazgao.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtujhdfo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2baacvmgl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ahybipgi.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ippwkojg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpuuzrn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfwytns.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2azmkmctz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tduyvadv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxalnukz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtpmppo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2tutgprng.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcoawxz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxwutnq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sotresby.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqrbikl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tezxwmvl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhojnisy.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtmsunn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2prfjsmlg.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2beqhykzh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbspitmf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxyycnc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhvrwsw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qegmjuuz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiraoqlt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xombvapu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2adawkiyz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2qsspxcvj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2konjxtcz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcrqljp.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tojvbbcj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrlxmkv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2adlbmecq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcmlhmj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2smbzdlyk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dxivtrii.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bytfgaky.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrlffcz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nqemadzw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lozvayec.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkpkntt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xetmorew.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hutnfgwx.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlvwqxj.html


<!-- 参考信息 -->