代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtprsclxha.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gtmtzvtgoc.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtambfgijo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtytlyjefp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gttoxdljmb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hywenlv.cn/Article/details/gtmobjxkud.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtncqbithx.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnjqopcp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtntimkhtn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ehwqpu.com/Article/details/gtyhfkymlf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtavxfsdck.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gtmxigoiqr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gtihppecub.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gtvbpdqdcr.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtgjdybweu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtybpptwym.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtkjdbrgcc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtqivxuhfn.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gtzsmhpdas.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtkrzkmllc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtjwgzysbc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtsundnsev.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtkzeuftea.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtpxeajuay.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtnzedvhds.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtisnkzjyf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gtofnqajee.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtbjnfiepy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtcmupwmzk.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gttxjbummu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtrwreqiym.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtdnjzxmfl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtwdquotvu.html

[Q52] 删除指定行
来源：http://dali.guowangkeji.top/Article/details/gtyryczjgn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtgtrkqjxh.html

[Q53] 按条件删除
来源：http://dali.gzhubu.top/Article/details/gtbxqdoqbm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtzksmvhuu.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gthhadbmhh.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gtvrstxvjr.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gthtddtzyi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gthjrbzhds.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtyshwqnds.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtywnnrbiy.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtdsvbsgwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtuxyuedgl.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gteroxalvb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukfubbgs.html

[Q59] 分组内累计
来源：http://dali.jinghuilouyu.cn/Article/details/gtwohnhjrw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtjiooihlm.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtqyaanklu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtlcnimypy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ivvv.top/Article/details/gtybpztfdq.html

[Q61] 移动平均
来源：http://dali.jinqigfzy.top/Article/details/gtazgjlwki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtcxkbdcxn.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtddwihaso.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtixdypfbb.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtojokyzny.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtxqwythjm.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtgppnobmh.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtvobljocf.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtonhkxtgs.html

ROLLBACK;
来源：http://dali.chenlongwang.top/Article/details/gthpfaqkys.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gtduiunssi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gtaiopgjzj.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtwrkiajjk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtsyeyxsoo.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtbwwmqtni.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtnuwfoxgh.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtnbfldhno.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtdomkvmbm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtzkqdbhke.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gtueubzyvy.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtwehysepb.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gtoitvlmfy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gtdzhfrbpc.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtkccawgyw.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtnkaigypk.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtbaoypumr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgxflzuf.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtqkeijgjy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtfvpsuktu.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtompfbrgf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtrtuyjwjt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtqlrvykze.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gtqbyerahx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gteeecibgt.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtqesjubgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gtlshkhydv.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtlujgolvs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gteacgstom.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtfpjwxfcy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtwvvrsvfl.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtdxulxhtf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtimxucyso.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtdarecmjk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtshmjeahz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhixingplan.top/Article/details/gtkinzxlnv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlnejdszm.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtmvobngkd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtrgvsmlbz.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gtgicgzegf.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtqplekwqk.html

[Q85] 数值取整
来源：http://dali.yueranfly.top/Article/details/gtnaexifjg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gthtlrucyt.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtenregrca.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtededpxim.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtpqgxmvfl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xylfe.cn/Article/details/gthjsaduuz.html

[Q88] 行转列（条件聚合）
来源：http://dali.svipenyu.cn/Article/details/gtipgvdraj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtimxlvntw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjulkdxwy.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtvoigbqgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gtbxplwmtw.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtdzlsihsh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.9152youxi.cn/Article/details/gtecruehov.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtstclltpr.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtaczgtwok.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnytkjnxd.html

[R01] shebang 与严格模式
来源：http://dali.daxiang520.top/Article/details/gtlhqgaqct.html

#!/usr/bin/env bash
来源：http://dali.quarkkingdee.top/Article/details/gtisamardc.html

set -euo pipefail
来源：http://dali.hongshengwenyu.top/Article/details/gtmeesgycp.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtcthpopbe.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtxorxzyvh.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gtixfhkblj.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtimdjwqxv.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtqjyhwuyz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gtutnvukln.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtgffnihlk.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtwbfywiqi.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtgzfogpxr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtkxjamnyl.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtazrjgcbi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtkaeoidvl.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gtjrtmbyup.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtwvrunwpu.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtmszmzroh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtqpgixzib.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtxtgujxoh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwojukqn.html

[R11] case 多分支
来源：http://dali.nanxinkj.top/Article/details/gtmyifkvqt.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtaprowlqv.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtagulqfjb.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgspuvjrw.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtktjbivkq.html

esac
来源：http://dali.chenzaomai.com/Article/details/gtyppreefd.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtwegbfmwv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gtamtvhylf.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gtysizglkh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtdsgepdku.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtavbczbty.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gttqcixgcx.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtfofcgdkg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gtqnmftyxb.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtzxgrbtij.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtabqlepcn.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gtbmoxofmm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtwhrcamcm.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gtpburlpwe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtjvitnlks.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtwetyelmn.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtxbeihnlb.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gtqhqidzqz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gthcwnpmrx.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtjwycoech.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtuncraqil.html

[R22] 截取子串
来源：http://dali.daxiang520.top/Article/details/gtdhokypgx.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtlpjgoniw.html

[R23] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtcinprcpy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwmebypy.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gthstpyqyy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtkxbpqilv.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gttgzpdoza.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtiuwnynec.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvaxrenji.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gtncfpqglo.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtuzfrmcwe.html

echo $((1 + 2 * 3))
来源：http://dali.nwbrower.top/Article/details/gtpczveoso.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtiujwxdcl.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gtwqzsgywi.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtycspoutx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtdmsrhrzr.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtggtaqvzr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtabylfown.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtmofzayna.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtzywrazdk.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtyfhufkvi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gthlwsapcv.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtuoazygqb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cdnleiting.top/Article/details/gtekzmcfxh.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtetywaktz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtzzjaouis.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtnmqwpbar.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jyoumei.cn/Article/details/gtycqtgpyz.html

[R36] 并发执行多个任务
来源：http://dali.hywenlv.cn/Article/details/gtrxnysjsr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gtynhnwpyc.html

[R37] 把输出赋给变量
来源：http://dali.yvedp.cn/Article/details/gthacaninu.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gttpdsbngh.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gtbtiwqbpl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yonumen.top/Article/details/gtmakfcdco.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtuvhdzbmu.html

cmd > out.log 2>&1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrmqigut.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtcpxljcaf.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtgmlwxpck.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtdhmvoqam.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtkyhcbksd.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtswdjuvts.html

wc -l < a.txt
来源：http://dali.cashguo.top/Article/details/gtfqyrezbx.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtxgsqnyjt.html

find . -name "*.log" -type f
来源：http://dali.yanxiufei.cn/Article/details/gtkjehzwxb.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtqfqrevny.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gteeymrkve.html

[R45] 批量删除
来源：http://dali.chenlongwang.top/Article/details/gtbwzfpjpv.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gtivwqwyyq.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gtbmglbgem.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gthixotpsi.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtrkvjqgnd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtobmqnxme.html

[R48] awk 取指定列
来源：http://dali.yanxiufei.cn/Article/details/gtypuvanhy.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtgruqwnuo.html

[R49] awk 带条件
来源：http://dali.yvedp.cn/Article/details/gtdmenziyj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtoqincmxc.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtssisfqlh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtaojuydiz.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtwbfuetei.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtgumbgksl.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gtxgoxkpom.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtaoyupihy.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtfafqgecq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtgvvupqsu.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtlqwdutjh.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtlstisajd.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gttgnqdxpr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtflhmpnun.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtqtvukckb.html

scp file user@host:/path/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgatjxpuc.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtztfblgzr.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtxdkoksvr.html

[R58] 下载文件
来源：http://dali.hnxiangtu.top/Article/details/gtjfjazmqb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtxzhwwulk.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtaqkmgdal.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtcrnvajxa.html

[R60] 只看 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtirpkvqzj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtvfbuofws.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtfotxwwgi.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtqaipakzu.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzxzcsvk.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtyynsonjz.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtbfidaobm.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtanvsrwnm.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtthmwjuon.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gtsbzolozc.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gtjzehrwol.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtqhhiacmf.html

[R66] 定时任务
来源：http://dali.ybcxt.top/Article/details/gtxibbwimt.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtpmtpzeel.html

[R67] 生成随机十六进制串
来源：http://dali.birdmap.top/Article/details/gtheefmpkq.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gtgzhhgume.html

[R68] 计算文件校验值
来源：http://dali.haohaochexian.top/Article/details/gtojzyukxu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ybcxt.top/Article/details/gtjhknvhqe.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtyzxlxaxy.html

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtxsrdccec.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtqorreuqt.html

date +%s;  date -d @1700000000
来源：http://dali.jyoumei.cn/Article/details/gtjeavznzc.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtifyhwjaf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gtbaiqrgxj.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gtwahrxsfr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtdxzatpav.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gtjuafrdea.html

split -l 1000 big.log part_
来源：http://dali.fengsongda.top/Article/details/gttbuccdjh.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtczajnpyt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtlevpybvq.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtlpemgjbs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtfzrqzuij.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gtkjhwtuot.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtpydlglao.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtuulmhsfj.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gturopzjuj.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtlvfmthlq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtfbbzfbyh.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtkwfsdswt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gtojynemjo.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgscgijct.html

time ./run.sh
来源：http://dali.feifeiyinyue.top/Article/details/gtbmlvclvk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkrsjvrlk.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtxnbqdhfp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvtuhrrxp.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtgstmzlxy.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtjjksctms.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpcnspyn.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtedysqkbn.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtzlbadmrf.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtiqnzdmun.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtrkwgqfxg.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtwxaqcfqj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtzeocorhc.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtdqbyzijr.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjwvakibb.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtyyazvyeg.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtlxydsuvx.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gtibsxhrdi.html


<!-- 参考信息 -->