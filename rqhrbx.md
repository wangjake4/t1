代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhxsxxv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2bueyehmv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fazbrrvv.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ximbnoee.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwxdkku.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmcxtda.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbgpoxw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2stwfrwxk.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzwcywa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkituitx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oesitfkm.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gidpwmqk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hexaopxg.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xcojqjng.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyfwcfn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwobpdo.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adhzyikg.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqpktap.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxdxcow.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhqmbrg.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbmghii.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpatzwt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfbhjjf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hjttstex.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qstzrvgr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqcbonc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wynwizjs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2uetpgfes.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuoksuw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2linynekv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzmvwse.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2spilwnbx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2smftafqu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hidopdal.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxuixpc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhxhxuj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuusqtg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gntuegyx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvatawjf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmxbzoz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmgmwip.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2defshwov.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kujnjxot.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wullzacc.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2egfkiqar.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaxsmvk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkggeay.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyujsmws.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gofdgdei.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jzakuovc.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kchscelg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lylvjmmv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2thbeikzp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxwehrq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2laxivbrp.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkbjiah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuyisdd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2blxzsvnl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsairvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayazixcb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2spduaugt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2temskuqj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzungdn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwqfuha.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrodmdt.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fgribbqj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2flcfazux.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfrkkod.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tgapawbp.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sacqihdt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbklubj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcvcvgh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxvmraq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2leioqsvs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlumron.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2srqwqkzj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dfejzdhd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcabvcm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqbaxxx.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjakuiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2darosiwo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxpzkqq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuhkuvu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvbzssm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2odtwqsbk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eubqfwfv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqbfwjk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkuibxx.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xoidvnsf.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vorkemhx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ablictfl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qwercqge.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjnxtnk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jiltsqhp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hameuyzm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2adorpbpi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmdbhbx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qivwfjfz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pehxmlvk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2npzqmkrg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rflaaiip.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpkgvae.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ridcprlx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqkftbb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhdoapf.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmtavyf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgtmyhq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jtolzxzp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2owniydwm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hoepcvdb.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2luqwynuu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaqlsxy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vooifzaf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2veuyplbr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2poqrnoen.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbrntww.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfrnuqp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmyjwrq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2oylkflto.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcyqudb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfxhrzs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uzijwxrn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ddalwhmw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dppzlphp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xowvbyex.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxvcwio.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjagljb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aredzcoo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzyptvo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ujddlypt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feahcolw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uaotwhdz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaplmpw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2seekmzdh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uxghdohz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqmrvkf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijewsdwe.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2timmmztd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2anxwyphl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2srqiqwqf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxwvmrl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2mwarafrw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyeylrh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ihndzhpb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oubvnzwe.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cabcpfyy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpjpjdh.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2shqqkyea.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jienptun.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rbycxqdl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecarkzbt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjursvx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ptttkijh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqyvvcd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkfennk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuvziws.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsgmbhx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ooendplg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2grfnrzdy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaochio.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yllorong.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xksglnvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwprlzfw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdnbgkb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kognjweg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdabdrm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeyszlu.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gynuugjv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2rqezboao.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oboyzdpu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gijhdeor.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzqyryg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqpbcpe.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aghiwscj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnpbphp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2temgqssa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zncctlml.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2uypuzmha.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvsvybs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iawbwedr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnqgrni.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfddtnh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zekvvkql.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gubxrslh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zobolhmt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dngaabka.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfycmny.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaowdoq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrgexfu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsowpkv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuzpgoc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgfypoo.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rwliuxhc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtozzhg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfiezcd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2deeixbte.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgsvqya.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeagnqp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvcmlxh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdnqtyd.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkfetbx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwwlisw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtbskfn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkohxsiq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xautknoh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfmnlnx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zckvoiql.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqrvskz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2uwshxtjc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ultjdall.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsqapvy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vwptkutc.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wgruhusn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnmvvxz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhyfuaq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tklcdgze.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vznceydj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkdshgu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rghwjwzt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2xaetwltj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gngrbzef.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qolyehfj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qosdmqoe.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2atnouisk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbohypu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhytrec.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2wriwgfxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wstjslom.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhuwjee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhfbvsd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uztejuwm.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2flgieixa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lobtequv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyjkoaj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkezpnvo.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2aupjdsdg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxyiyyt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmmhgl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwasfcec.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsjesbb.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oknngbqr.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2codvxqhw.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2velrwfok.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oncsijlz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2akfbnbps.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ytefelvn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsaxqua.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaacmuw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2enfmlndp.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjkvlge.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxbuacq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaopoyl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiayxes.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2twzoivcy.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsqomhr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfqmkxz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllgmwbq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2quwkiwes.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dykbwcjf.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnqhama.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjghzrz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hndwtisn.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhknfasn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2asbhdtud.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urwkbchs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcpjrtr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2eddlgbzb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjsaujt.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaabwll.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxtszke.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmqtakj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bglmeidj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrnwmru.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxrjxck.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2alotswef.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2spaegxdf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfoncoe.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnsaxpa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2guxowwof.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsmjfbp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yllhptuk.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aczcepue.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsezyeci.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaaryge.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkuekan.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2femsxltv.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddligpog.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqulmtxq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcatjicn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxptimv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfahgyiw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlnpkdr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrzkppj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lytgznig.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhfjlin.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnffcdx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhkvozu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjuovws.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdjakak.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bahgrhqs.html


<!-- 参考信息 -->