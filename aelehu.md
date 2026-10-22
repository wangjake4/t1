代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtvdzntdmo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtkughcbec.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtbhzlzedy.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtrzzahkzs.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtpojybvql.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fengsongda.top/Article/details/gtznoveefv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtmbmavoan.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gtauwuffqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtbewpbxcr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtmktrrtrt.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtxlulqyas.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtgskmscvi.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtyozcglnh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtqanmywop.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtkgezfwyi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcwakafp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtpwdakoca.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtwzpjlzdp.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtwagzthec.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gttpdsbnje.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbrbspxc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtdvkeyjam.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gthqjyyewm.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtejkumgvg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtdbfmwsen.html

[Q50] 批量更新
来源：http://dali.gogol.net.cn/Article/details/gtzfqpkodd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtthnjttbq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gtuhnoalbb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtmttelvrb.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtkdvuahzy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtywdjcoap.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtplwosddy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtlascqmqq.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtnxvbbvak.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtmiujgxwj.html

[Q55] 排名（并列占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrnwieyu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtczbjhilr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.iojbl.cn/Article/details/gtlzuxfkig.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtzgzlfdmn.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtetufeeoq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtumhghigw.html

[Q58] 累计求和
来源：http://dali.hfpthk.cn/Article/details/gtcwewseqg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtbwvjvjpj.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtbvanroly.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtjilqikvr.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtfayycoqt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtiasgetrn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtnjhxllcb.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtzbdatzau.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtyxssolsn.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gtyiaxgifc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtfuavtivz.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtismfvixv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtiaqyhekp.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbxcbpxj.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtkvoiqzkn.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtltiiqwxf.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtzteawacq.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gthsyaspza.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.andypj.xyz/Article/details/gtxnvyqqxg.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtgztrqhom.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqobdqaaw.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtepkrojew.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtqwzfpqbf.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtpmgzumrk.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtfemsxdsv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gttwyadwtv.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtroncxfxz.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtgqfgeisr.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtxftwmngs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.wangshuangyany.cn/Article/details/gtarwvwhtb.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtydsgddky.html

SHOW INDEX FROM users;
来源：http://dali.cheryme.top/Article/details/gtsnryqqwv.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtotquqkux.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbjhwvms.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtnfatganu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtuzidmvqe.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtbggvcdea.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtwysbyeue.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gtfhrejbnr.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gttuzorjxw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtaddgxhht.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtjrytdapa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gtvvbtujsi.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdtdmrzs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtarmfflpl.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtbuvwjfpb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusebmjyw.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gthqlmdcvw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gtwejmteim.html

[Q81] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtiwivbiqq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfxelosky.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtjmeoevsc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtjspveudb.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gthplargpu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzhhxxdve.html

[Q84] 去除首尾空格
来源：http://dali.hywenlv.cn/Article/details/gtexijjoxr.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtoavvezps.html

[Q85] 数值取整
来源：http://dali.jyoumei.cn/Article/details/gtobylkjzr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gteonxnvcy.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtebhpvjor.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gttssidltz.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gtnhkgbuyv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtumrwiovn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtqcuayrfu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtzgyyhwgj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgkqsaywv.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtszpnmksi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtokmxwrny.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinwcblrj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhoulong.xyz/Article/details/gtyiouqgut.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdlnkhhyj.html

R. Bash 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwaetfxom.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtyibramps.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtpkuyuqzp.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtdgaybsqm.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtzvzltguk.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtmyxhdsex.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtrzufrxyf.html

[R03] 只读变量
来源：http://dali.hywenlv.cn/Article/details/gteqehgxuo.html

readonly PI=3.14
来源：http://dali.fengsongda.top/Article/details/gtpjewjnzw.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gtzfwplgsc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tanke756.top/Article/details/gtbaigvoif.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtjlheiavv.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtvgrcqfgb.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtevaxvnsn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadmetafe.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gttnmnviqb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtakedqgki.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtocbewsdd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gttmgevfwk.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtnexbbvek.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtvggliakz.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gthqyzttwi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.bjfxy.top/Article/details/gtrpcgxtjg.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtresmcnwh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtbowhhwmy.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtqcykyizh.html

stop)  echo "停止" ;;
来源：http://dali.yj20258.top/Article/details/gtfubrlbwi.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtusogvwwk.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gtdyhljvpu.html

[R12] for 遍历文件
来源：http://dali.daxiang520.top/Article/details/gtgwemttjd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtxngpvfhw.html

[R13] for 计数循环
来源：http://dali.ehwqpu.com/Article/details/gtvdjpemhm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxryoevy.html

[R14] C 风格 for
来源：http://dali.ehwqpu.com/Article/details/gtnmoxcvmi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtsealxtuz.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gttihqltwp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yanxiufei.cn/Article/details/gtkmkkgsuv.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtwfosohsp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gtmqzzxwik.html

[R17] 数组定义与取值
来源：http://dali.sweek.top/Article/details/gthruzrwet.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhengqikj.top/Article/details/gtauvxantw.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtjthszmdw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtsmemjrka.html

[R19] 数组长度
来源：http://dali.316326.xyz/Article/details/gthoaahrsv.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtedpguagf.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gtbeckgcer.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.havefunace.top/Article/details/gtadhmgzqo.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtgwlddqxg.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqhwszry.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtfifyhzij.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gtrfoqzwew.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtvliqrnfw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhixingplan.top/Article/details/gtndoskveu.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtydvkmqen.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzcugchw.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtikbdzhuh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetsdfqns.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtgvdoyefm.html

now=$(date +%F); echo "$now"
来源：http://dali.jqgfzy.top/Article/details/gtixcijyhv.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gthpgmjgcx.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gttlxvyicu.html

[R28] 浮点运算
来源：http://dali.chenlongwang.top/Article/details/gtruplucwd.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtoraigdik.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtlwsyzspv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrtkprez.html

[R30] 函数返回状态码
来源：http://dali.xylfe.cn/Article/details/gtxackftvy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtmrnwjpug.html

[R31] 局部变量
来源：http://dali.cqqwz.cn/Article/details/gtmykyqxwm.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtnfzgdm.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfhmtkfc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtdirmnnhu.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtvboywrbj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtbnjapwjg.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtcwkjnsni.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtaspraqyh.html

[R35] 后台执行并等待
来源：http://dali.hnxiangtu.top/Article/details/gtzfsfccqq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gtzhoskqkm.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtyuojqcse.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtcyvzamag.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtakkdohyd.html

files=$(ls -1)
来源：http://dali.hnxiangtu.top/Article/details/gthrluebew.html

[R38] 管道串联
来源：http://dali.yonumen.top/Article/details/gtvrqkuivj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtcbklbszv.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtlnfnjyki.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtqzgetuao.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtmipnfsff.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtbbnzkchy.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtcwfbpnfr.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtrowpccfx.html

[R42] 输入重定向
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyvcrons.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtiubpuhwf.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtmjiwzbtg.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtrzondufi.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtpyelayif.html

find . -mtime -7 -type f
来源：http://dali.jinqigfzy.top/Article/details/gtsjpadblu.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtmhtmqqbu.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtlazabwhw.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtlipsgftu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtaylrcles.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gtxdxvwwfu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gttmrtbyjt.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gtwfegkkbh.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtjayyczxn.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtozwtqdtk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtkqwqsyug.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gttveeugtr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gttruhgibk.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtffnxzkdw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gtosbzoqvs.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtnhstzrwg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtgolbfetd.html

[R53] 查看文件头与实时尾
来源：http://dali.ppjwa.cn/Article/details/gtkhydgato.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtvgfpzolr.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtfrracbdf.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtjmzpwkbl.html

[R55] 压缩与解压
来源：http://dali.zhiwuduotai.top/Article/details/gtqizxybvu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtjncbngrx.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtudszcmqv.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtvzckabgj.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtwzctywlm.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtnnljekkk.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gtihjcllqa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenlongwang.top/Article/details/gtomljorep.html

[R59] 发 POST JSON
来源：http://dali.aibaodan.cn/Article/details/gteettmkgk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtoztckepc.html

[R60] 只看 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtarfvouez.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtesqagwfe.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtghtnqtrr.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gtyqorplsb.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gthbuecdtl.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtjelamirk.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtmcnxdgoe.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gttdaozpmn.html

[R64] 结束进程
来源：http://dali.hammf.cn/Article/details/gtgzdbiavy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtjmhlddml.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gthxxyotuq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtnghcplla.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtclbebrjx.html

crontab -e;  crontab -l
来源：http://dali.xuetiantiany.cn/Article/details/gtgnjmfxnq.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtvyfeccmu.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtxkgtzpgg.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtbtvuyeen.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtpdzsfywc.html

[R69] 生成随机密码
来源：http://dali.hnxiangtu.top/Article/details/gteazjrcid.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtqvmcwshx.html

[R70] 时间戳与互转
来源：http://dali.tian-w.cn/Article/details/gtapsastae.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizmvxxuf.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtlzgvleim.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpachkgid.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gteaquxiaq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtgenyoydm.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gtfjsoebro.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtcjbfwkat.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdspzrrmg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtpwxdzjul.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtixvygvvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gttajhbwdc.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtpizujmhg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtewchbdjw.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gtstlrjpzc.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtenjrfevl.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtjhhwhazi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtqdancsbx.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtulmfqmjz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtdvdmwvrm.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtxgutwfbv.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gtwxusceyz.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzraeebho.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtgqphascn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtihoqjeeh.html

[S01] C：Hello World
来源：http://dali.tanke756.top/Article/details/gtsqolzykf.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtkuouyvdk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtirejsgeh.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtlxoaddkw.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gtkqxosgnz.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gthmujfdmy.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtnyqswjqs.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gteziikerc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtcfsnihvl.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtkkuyuuzi.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtloacpqzb.html

[S06] C：字符串比较
来源：http://dali.sxryk.cn/Article/details/gtmyeynhke.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtxybjnqww.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtzcwiqdrf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtnsgtknof.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtlqaxcyli.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtcqcarzmp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gtnslqmzlw.html


<!-- 参考信息 -->