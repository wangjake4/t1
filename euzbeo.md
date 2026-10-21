代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtrdepcchz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtwqzasypk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jiagoushi.top/Article/details/gtcpvszokz.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gthcrbcamo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtsgjhttcc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtudmzqpfg.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtlmpjnvpe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gtqvkhqxwe.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gttzspjapz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fengsongda.top/Article/details/gtaiolmqvj.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtyjhcobvh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gthksfefgp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigfzy.top/Article/details/gtcywpyodx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnufvkdkd.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtkbwqhapk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtmxzswmys.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtlydslleo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gtvdzpehih.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gtrbhssyix.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtnccxfbdz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtivjfaftf.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtitbmdgtd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtgiwafqwv.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtxnmvfmjh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtpwqkfrem.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gtkowuicps.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtcqpyzqdp.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gteungrrac.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtfxlakuzn.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtinkcxjbz.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gtepspgnec.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidviiccp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtbzkfaeyl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtqhgyywnt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtxhtdwgtv.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtlcozxojt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtteqnemnt.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtesauvygb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtangvnbuh.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtvmzybtng.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtsqehknqs.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtqcgtccvi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ehwqpu.com/Article/details/gtghseintn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtqkignpvl.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtkudogwyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtfscbdwos.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gthkqnfbzf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtlsuhvheb.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtsqyslngp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtwibvnrho.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtfytelutb.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtjxihvjke.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gttelolfnr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gtylofwnal.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtejnwjkbq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gtpblirgka.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtruwiktgs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gtkvppkatl.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtmapchsfm.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtnbyatjgi.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtgqsemzfa.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gtjzgtgpyp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjqktdyk.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtfulquzux.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtliieadla.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtyskglypr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtykfersyr.html

[Q72] 查看索引
来源：http://dali.jinqigufen.top/Article/details/gtkrmtowzs.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gturvqdkml.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtwaisltpl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtmstcruif.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gttqmjweck.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtsavjummf.html

[Q75] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtcoyxaxbf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gttenxrsbr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtsuzdscnn.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtcrbzieoh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gttuhckttw.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtnhvhxhau.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gttnjynfgj.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gtmhvzlsms.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtwuzhggns.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtgjcpdkzn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxvbqqyt.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxogexdct.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwuebknzz.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtqcxoxpul.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtwtvgfugz.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtfxcuiutj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtkcggmesr.html

[Q83] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtpxcriqqw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtbwymdczn.html

[Q84] 去除首尾空格
来源：http://dali.ehwqpu.com/Article/details/gtgkykwffb.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtwbresuil.html

[Q85] 数值取整
来源：http://dali.tianlin.xyz/Article/details/gtarzlpwsr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shangyingyoupin.top/Article/details/gtxgqqgbgf.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxakscalh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gttkwqbpes.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtjeugntgt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtgpzcguqx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gthiohzcpe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinghuilouyu.cn/Article/details/gtipwpxwmt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttrwsqimo.html

[Q89] 判断表是否存在
来源：http://dali.yonumen.top/Article/details/gthglnylch.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cheryme.top/Article/details/gtoiqociwx.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtbjmkophj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtngokyckl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqqtzbluh.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtlkmzljac.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvxqdgfyh.html

[R01] shebang 与严格模式
来源：http://dali.chenjidiqi.icu/Article/details/gtxtutmrvc.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtpsyxkhpy.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtwaipkcfs.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtavjuimtd.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtpjrqolvg.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtgianbwzt.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gtwncnupfa.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtcegalhfj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.smart0.xyz/Article/details/gtksyynrvz.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtoiizdjpd.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtqdwlssau.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtgwjnqrlt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtjyyfygdd.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtqwkglucr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtypggbxyd.html

[R08] 数值比较
来源：http://dali.hnxiangtu.top/Article/details/gthymsdisf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gttijhtuss.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtrlierjqg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gtoyeccpow.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtunhayufn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtmaxidczs.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtxrqdgghw.html

case "$1" in
来源：http://dali.ppjwa.cn/Article/details/gtuihkicir.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gtdyftbpfq.html

stop)  echo "停止" ;;
来源：http://dali.yuanzhike.top/Article/details/gtveycyxkn.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtfwwlnmes.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtwkdizqlx.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gthjqjgxqq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtbpyyigtx.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtfxsioevz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtkuanhhqh.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gtekkyiirh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtcphjrdkg.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtornlicbo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gtbcnswztb.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtvfsswjrc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtgejpvyom.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtscfbyckq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtlgioesei.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtbktycalq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtwufegzpe.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtcjytpmnx.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtzrqutzcn.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtapggyotx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtstdxyytp.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gtityhnpgv.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gtnewwgsxi.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtsdttlwkn.html

echo "${s:0:5}"
来源：http://dali.nanxinkj.top/Article/details/gtauksnhdy.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gthglliyyd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.316326.xyz/Article/details/gtimnutzxx.html

[R24] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtarhhqvgx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gtvyxglfew.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtuseqndgl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtmojzdujb.html

[R26] 命令替换
来源：http://dali.redwolf501.top/Article/details/gtmjxgkrmj.html

now=$(date +%F); echo "$now"
来源：http://dali.shangyingyoupin.top/Article/details/gtygzhibal.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtszkwjxyd.html

echo $((1 + 2 * 3))
来源：http://dali.yongpay.top/Article/details/gtadzhdxmk.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gtmdjqmsef.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtjkjfrsip.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtcmpatold.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmstehxxy.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtmhfewwog.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gtznohjkfd.html

[R31] 局部变量
来源：http://dali.yj20258.top/Article/details/gtuwcwwbnu.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtoycdknly.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtwvussmku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sysykeji.top/Article/details/gthdywivfz.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gttqoahsdr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtcgdhyiry.html

[R34] 退出时清理
来源：http://dali.jinghuilouyu.cn/Article/details/gtonxkotdo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtxoawsmxp.html

[R35] 后台执行并等待
来源：http://dali.meibo888.top/Article/details/gtjgjcrpvt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tanke756.top/Article/details/gtfoodhdmh.html

[R36] 并发执行多个任务
来源：http://dali.xuetiantiany.cn/Article/details/gtsvcqfbkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtlkgzmtps.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtvjjtdzpq.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gthbefzgdq.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtlvaevhvc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtcrkardtc.html

[R39] 重定向标准输出与错误
来源：http://dali.ppjwa.cn/Article/details/gttumywqnf.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gthsetooaz.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gttrhzxfjq.html

echo "log" >> out.log
来源：http://dali.gzhubu.top/Article/details/gtolkqvumu.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gthsmnlqar.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gttbtfyjhe.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gtkkziyinr.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtwpabdnjk.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtyfglfgep.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtytavzfbm.html

[R44] 按修改时间查找
来源：http://dali.sysykeji.top/Article/details/gtkcuazyfu.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtqufnpkfl.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtharfkdey.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtnwzwgdwy.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtvgprfncx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dashuyun.cn/Article/details/gtuodbhssu.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtnjuadeik.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtsmxawsok.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtiimxlclc.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gttglwmlpk.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtiwrntnmm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtmkrgfvdl.html

[R50] awk 求和
来源：http://dali.shzxlz.cn/Article/details/gtidfxetsy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtuahlread.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtmtumhmib.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtutdsextk.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtmoquczpt.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtmhtjvgif.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtktqhhzhl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtofveojqk.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gtucgawoah.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyflgdme.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtutgwyijb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gttntxkcwm.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtahhelcft.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtggqxjucs.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtqrhgrrwa.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtpvarcxpa.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtbnhfdenf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtzvdnaifo.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gtyoptqdzp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtchlaefwu.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtwlklqqkd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtrywwvxgs.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtbbnpsmky.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtrjsgxnlz.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gtrfjuwmdm.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtsbmjdweq.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtkatbxidu.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtaoigjtib.html

[R64] 结束进程
来源：http://dali.pycfn.com/Article/details/gtkeqxchov.html

kill -9 $(pgrep -f app.py)
来源：http://dali.c1oappe.top/Article/details/gtxxkbdiui.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtijvxjfbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtbuorcqgm.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtllifcwia.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtndnjwrkf.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gtkbfumaqu.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtgdjkypbh.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtxhokelsj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtvhqrgmtf.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gteqzjlcuv.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtzzirsqng.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtbkdmhfby.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gtpujbxzyw.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtginfeczx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujdqqjdq.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtccondxcm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtsbljwcsb.html

[R73] 分割大日志
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnynmnek.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdyqhkap.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtspyqgjjh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlhbrvgf.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtfpntwxhb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gtipvsulvp.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtwbexcemf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtehravgud.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtkkdslzqd.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtciuufkck.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtdywwtdqs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtwmzwtnzn.html

[R79] 解析命令行选项
来源：http://dali.guowangkeji.top/Article/details/gtaaotbhuk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtiupscqlv.html

[R80] 查看脚本执行耗时
来源：http://dali.redwolf501.top/Article/details/gtkivdnfxx.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtgidrcdjn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjgpffkiu.html

S. C / C++ 专题
来源：http://dali.yj202588.top/Article/details/gtgxmsilpw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdtlrkgfn.html

[S01] C：Hello World
来源：http://dali.zycfv.cn/Article/details/gtkqtgghuh.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxytfqoct.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtilwtectt.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtxvdrsced.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtvorfkytt.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtkwlkthog.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtogrfxgrf.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtorwyufvs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtwgwxjeyw.html

[S05] C：字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtfjgavqxj.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gthfljqpay.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtopdyfted.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtegczizlr.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtcaeugvoz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gthunnrepm.html

[S08] C：动态内存分配与释放
来源：http://dali.jyoumei.cn/Article/details/gtxzdbqfis.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtrysdowwv.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gthgqgcvrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gtjtjphedm.html

[S10] C：指针与解引用
来源：http://dali.dashuyun.cn/Article/details/gtdgdpfajk.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtbqtyyrqf.html

[S11] C：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtydnqmnjf.html


<!-- 参考信息 -->