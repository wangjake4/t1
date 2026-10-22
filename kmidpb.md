代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotmgrwc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pekmtnlw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2klhtfnyz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeeiyny.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iibjvtni.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tujquitf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2remrrkvm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhfqiri.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuzwdwa.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhrfzej.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jusyufgb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2egiqysgo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2akvcqudb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyfdwok.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdmgmjq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2blqgsxrg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixikilic.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuswiui.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqvjngq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wwedgeim.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enuxvrdw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yeailqpb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaaeogp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzsxlcb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdsnxg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawlxaa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxqxsve.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhwvgyu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2orjscepq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2srakairy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwftzkn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnkfnoo.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2trfwakmy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyekfde.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2domqxwfe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2osnipmhs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lovmkwmr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpfujpj.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xgobeeur.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htnygbim.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azgzoyrb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgyrgeg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2waehxvny.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2phpackxq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyexuftn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ssihugka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhofhrl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsyzlwz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2svxkzgvn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2letvintr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfmytwh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2slamkipk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gjyyhaxw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnooysty.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uemhvwfr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzrmrqa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ytifsqmw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2egumsubu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdfdfje.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ummiozhe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcrngbe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeplbok.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qazqqgtc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbdonoi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xctoqxyt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpbnruo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qrumxcvn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jodlsyiv.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2usmuhpdl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuipmtdb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2czofndxw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2manwofil.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyzovrp.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szdvqgjc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqrkdvx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpptkovn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tjagmhqh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkkxcdj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tawofhwm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2alwikhjn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvptinzk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nktaesqu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unyilief.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vxokjhtn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wedcjtps.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfxbmmd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2stvcthnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjuatly.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hhffcixj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brabnsgc.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2koscbtot.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dottibvh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbujhpf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sefflbhj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxkdagb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdfwwpe.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpghfxe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqqsvva.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfoxtuw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwqcmiz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsnjpsj.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhzqgug.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlquspnm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2onyaplki.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzbdsem.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfweltu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gtayzywl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfbcxvv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2neoltigd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kauvoioe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wltfwznt.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoqlebh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2agsbxxvc.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2htfxnonj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgfhcxw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpfhlon.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsdfgpy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoiatik.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtbjkzl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxxqbxr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fmusweav.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdpoqln.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vrchunze.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyticpj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrellif.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcttryvi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awtuxxdj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ossmxudw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wslhlyfn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2alrstbov.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wazcqayv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2edkwhbre.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwgddud.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvsvfgr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhakkujx.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jirxinrc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgqdkfw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2coznbeii.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbnliau.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zojgwmna.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2odahvvrl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2doxffmqp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwqjxgz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpyanbv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2auvyhrna.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkgiexe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rstijcpp.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dftzchqu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhmheoz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvkicbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pppmdhcq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyuplltd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sftlqhtj.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvvnbbg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdrssab.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhifjym.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pubbuwgq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2njxpqkko.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyedjdf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdkljgr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2eepxtseb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvgeycn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdenzvp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2edukdskl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnnzcsf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aupzpyfq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2cmskvjhk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjyhggm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwyzmug.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kewyltpf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxegnv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvaldmj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2inuuwwub.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmtcvgr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2szkgiqzs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lieebsli.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfjdpef.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtncjcf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owvfqqdx.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fkygfknw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wosxkihu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tkooyfwu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kykuxrgf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sxctjfdm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxalsxa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkqbfvz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bndoougj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lelrrrxq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cymtanov.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmxivay.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdhekxd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2stpuxsac.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wuiqdnou.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2whrmcjjo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2djjslmeo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtwoedb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2reipkmil.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jsodswqf.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qahfuykm.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqtdndt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvofjly.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhhrogz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pigamspr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2aabhpdxf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsvubbl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtdcvom.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuqhdbf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdwvuuv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqywfh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmftoxwr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2twxrkemz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2apdtzpjc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2awfrqjpt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvagrcg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2durziimd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rslpvwnf.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyeqtej.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwtpaxt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmccrln.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzimrxm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2yllpayew.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnlbier.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehvtvli.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kakjzgav.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2khqbleza.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhropaf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzvdggz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtkfzrx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mpovxkhs.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2yiueahtj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ruftnfxl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xubckxvw.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfavcqx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbczdej.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhvzbel.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuruwwd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmezcok.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpeqtu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dymllvmb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bbynoalr.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cliaapfx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlryym.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpgyfvi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ushtxums.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfzpkfj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjgyptd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdpvujz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjphsdz.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnzfvlq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwflyqm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsqbqky.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2czsirkdv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2szhtjpra.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsjboxu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfxjoqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlykmql.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyzqloe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjujlme.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwbzcer.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kaemfeia.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hivoamja.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaxaksd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlogioj.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmsonkv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrjakff.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqzxgxa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdbbjbo.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuxizjm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqaaauh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuiodrs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmoniye.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tamxudwl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjrhlii.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2huqmrpqq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqgugio.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbkxhtu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjanpie.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkhxsbl.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2awzvulqc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrrmujx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dexushhj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxnqoar.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmjjlbm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gcriqjok.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qapjvdee.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnoubun.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvztetez.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rwthjjwt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsimdls.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvkmxph.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdgaxcq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zetspbrp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxnbluq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoehqbt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmhxnel.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtmcjro.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgurljzp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avqmqafd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlilmyul.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2szlcrvvo.html


<!-- 参考信息 -->