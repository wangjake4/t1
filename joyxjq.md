代发 wailian999

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgwxhfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2oexoiiee.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ombwtege.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2stfnzzsf.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aasjbuck.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wolrxxra.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmccomo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kofsoofc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdlaqsr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrdjsmj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ashqblpf.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2argevoyc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dikkkdkj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgflwxk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2psgvxtlv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2igbuerid.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2loyxkwni.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfudgcy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2recshfbu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2alyclypq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzqdmqc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzseqfr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2drymvwgz.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnzckgq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wydviopd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bxluglic.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gukgaebd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsxjgoo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pdudxqjq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxbhhdu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jixfndyc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtsejta.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqjovnw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2glcuxuop.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2viflvwcc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpidyyp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2voztvlmq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pscdbyds.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ridcealk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcclvym.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmhelaj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juepytqi.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkkvjfm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuyejux.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bplxxgqx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcktmjfk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2itzkwmqh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mybppdld.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kixcakfy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yhaswewl.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eoudsbgo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbduwja.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zejlvcbn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2oawuyjwd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jswwotkd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qydabllk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhjqspv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzabjoaw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2eutvyces.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrqhuk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbyfzhj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbtrzfy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmpfagb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbcemoj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hcghxcbn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfvvgdl.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtorlga.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tylbeuro.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbvoqvj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iviwzdjj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2brzpvsrk.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2naxvqfvr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clvybrsb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jmofvymj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzumuwrv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bpftmefg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fpllexru.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxgciqe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gcetklub.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2atldhlvk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2obngrhop.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhtrscy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuqqoqa.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzcpank.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxprbqn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2scdsuuro.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmuystl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmduxfhe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjtbavc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnkacwi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afodqfya.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hltoflmb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbkzufm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sadexwbb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cufzwrud.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luzjtrmh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmkusyx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdemnpny.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtfbegl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiebkej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jamtxvbl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxvkomd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oiisujgx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cwthqcyd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyagrbo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2owwtvnwm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgklfnmg.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuvgzjw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmnqlhl.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdwswns.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtelrmu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwyrugf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfpebtx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzpjatd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnycrpwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpqosat.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcoaunl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrowtfq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2knzaimlh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjolwuz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoczpwbj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgbgmpj.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2thkapfyp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktimkeyl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbkfpkl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bijujhnj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuwlbsq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xpurxijq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkexoiz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nbubzblx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csqscbmt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dhedveiy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2acmoaixl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmkboqz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhvamwl.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaqjjxk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gljyarfc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kqenkdyy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qobysfhp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwflrqt.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uskkifjl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2glwxtfoi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnnopvo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hmftghfe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2homrutzg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjzeqis.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdgzqdl.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhpkmsy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgqcgqq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbvmfog.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcbtbpn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgejiab.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhflogf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfnnlwp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbtsabo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvearbm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2xorjjiex.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uevchozt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2psxgeawy.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iafpnwwo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rilmephu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoizond.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqakisjs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2moiowovu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wifkmbqz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dypcxonq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kbodquwq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfptoam.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsviktd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymamwtkl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxtgufd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xplvmyca.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwpoiev.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tukehsqg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdcxwpm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzxflgj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2prlxxqzg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hxztvmdu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qmadwpus.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2culwlfld.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfhnhrz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njjltkiq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjxdevh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zaetnapm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjbzzbj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mecmbaxm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xdebxcbq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2buexygpr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxninzk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dagemjmh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jomzjouz.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sikfxofi.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmctbvb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrithfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeossyeu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2qyywiezv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmubfpp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpifcnb.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xiubepii.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpswzdo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sulpcmed.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmriqaca.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2loztlnbk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pljyvkot.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqwjezi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbubsuw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfzdyxk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzgkhuj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpisrnq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2crznqbhy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcfmeip.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fodgomgh.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtlyhay.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpvumwm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqlftbm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wefkljmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2aelxvtgu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enookkwx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbgsonh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2riahoeof.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2btokexrl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fygzgxxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaltzmz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkvogmu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2isihvtbr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2snapujhe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2uznvybhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysuvvdpe.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpmwlfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxlruqi.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tajvqcel.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2sduoeppy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tprzxvlv.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xjttomua.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cukrgyiu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlguehgm.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qinumcjc.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2sncslrjw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2dhznfarw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2segezobf.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbthcnfe.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2unmpbdcf.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2anaplfvn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2keghbngc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgiclcr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2knumrjcn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjukkivt.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2cdosceir.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfxjgmd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fxregjuo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsqyolk.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rznsbixg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlyzopn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnwtdyp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxypmdo.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nebvohqg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rokhkkja.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnfpvva.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxrhcaz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdrekuq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbumosc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhzchca.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkilcro.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2yfurhwdu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2njuiugkp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2puwgzujm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsseext.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlfbabq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvmnpxa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqewpcgb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuucuyn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uotsnrpe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnclyny.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnntbmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkakzbq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrixjzf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqcpekv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdhdpby.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgemvso.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2crgyrfqj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2txhowbsy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2guzqszpa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsaqvox.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xamcfmap.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrmsrel.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcqkiqf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgluaisn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2joqwjesm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmpbqrw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2baciweqk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yprogxnw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxheptd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2iaadwlxy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvolrsyg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnmwjhr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iniydhbh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mqahrxry.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emchdwqo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgpgryz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnvvqiq.html


<!-- 参考信息 -->