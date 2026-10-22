代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtfxddrwku.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gtpzpskzmk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtfusfzotg.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gthekasxzf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvgeheil.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtwjhswrok.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtlgwzvjpt.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gtgozvprjb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwutjqnks.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfygzimpn.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gthylyteoj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtlqmxxwnx.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtwhqwiiem.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtftgtqynb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtbuyunfid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtjbhsqgue.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmxvanoq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtbzvyctxm.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazdptmgl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtwjxbhssi.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtmgxkmowj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxinkj.top/Article/details/gtarrctpze.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtaujzyfpr.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtbqubmfhz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjknuufk.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtvteeqgnk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cucudq.cn/Article/details/gtlelwmhgv.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtouggkzzo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzyjjimb.html

[Q52] 删除指定行
来源：http://dali.yanxiufei.cn/Article/details/gthnggaain.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtqgnzssto.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtgozbttjl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtocdmfuql.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtmzmqveas.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gtxzmpbmyt.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gttnqvluma.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtdmomgspq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtwykcausf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtjeoujzbe.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkitzxxq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtuknsyzut.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtywrpmwaw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtjwuilmht.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtkzktyrez.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtkljdcwml.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtagbcvbho.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtiodroldk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfzyqoaq.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gthxmlnint.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfwasbjsc.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtbexlmdee.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtngxmrynr.html

[Q63] 开启事务
来源：http://dali.nanxuanxn.top/Article/details/gtklfewnnd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gthbpwdxlo.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtijkmprak.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtdolwajkp.html

[Q65] 回滚事务
来源：http://dali.chenlongwang.top/Article/details/gtloihywap.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtgksutfop.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtijuwmwzd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gteqblqdet.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtmhiqznew.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtjbtlrmwi.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gtwyrfmyga.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtdrpxfwzq.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtlnhgbjni.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrvpioto.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtazpwsgsg.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtjzpfxmir.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtembpvwci.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtbdadnkvp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjyjremv.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gthgbmuaia.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtmxdhbxpl.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtudfrljzw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtxtrlqdpt.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvtigjft.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gthszwofsn.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtfatgisaa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtdsqcdysa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtugnzmhqs.html

[Q76] 按天统计
来源：http://dali.aizwys.cn/Article/details/gtqgaxpwbd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gtlnxmhsfs.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtiorqxijc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtehhozlcd.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugnweuow.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtqzexluil.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtrhlittys.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtglgymthb.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gthylrtzfr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtlxnsaqfj.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtjmbhmjse.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtekkfeuyg.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtnyjcjlov.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzczphqdw.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwhhiqux.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtfdxgvfyh.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtntpbzite.html

SELECT TRIM(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtnqtsxfzl.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtomrowavw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtuskzhpzm.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtpguimxcx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtwnlracxx.html

[Q87] JSON 字段做条件
来源：http://dali.gotoacloud.top/Article/details/gtkupdrlwu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtuilybdrt.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gthquedzms.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tian-w.cn/Article/details/gtqwwwcjqb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtalwhxabl.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtzcwgamhn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtbaxwwxkd.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtvydrqhnh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzklbodg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttinejanq.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtqggqxhaq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfzircskg.html

[R01] shebang 与严格模式
来源：http://dali.quarkkingdee.top/Article/details/gtodepsubt.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gttszgmyqq.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtgzvfgerk.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtnkqmcrlm.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gtexzfznku.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gtzgxafevv.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtgytuscjh.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtsghwouex.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangshuangyany.cn/Article/details/gtgotwzfwq.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtphvbihpx.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmctjwkha.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtzcwtfgyy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gthloriwur.html

[R07] if 判断文件
来源：http://dali.zhoulong.xyz/Article/details/gthlnekhgs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtfjfytsir.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtlccoftdm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guannengcc.top/Article/details/gtslbfsdxz.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtdoevzrcm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hywenlv.cn/Article/details/gtvmbvorgt.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gtudvjoqhr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhixingplan.top/Article/details/gtzxuembsx.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtaydizdzl.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtyewplujv.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtoltddgxi.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtyyjwbuki.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtledhqvhy.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtiabjnxaa.html

[R12] for 遍历文件
来源：http://dali.sweek.top/Article/details/gtldudvyhv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtkxxhaxvy.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtiypxiyhk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtijnrlghw.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gthudllwav.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtrzszekhg.html

[R15] while 逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtobpxlsmq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gttjkfzabw.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtmnsoyikx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtagrceqch.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtzjsskohj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtwraphktz.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtnsceurxu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtnobtnzrh.html

[R19] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtyoytpfkm.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtgwlgewow.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtgeygflsm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtqjekogxu.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtgfxvkqnf.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtlelwklzl.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gtheynyaik.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtpezdycrf.html

[R23] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtpzlpklgf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtydniypkm.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtcvbfpude.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtisrnffot.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtytzqsjnq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gthhwbcyrv.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtrliyspfx.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gtijtrsjsq.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gtoixmmfhf.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdfclkjd.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtcmlszfmb.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtmgihifmn.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtdeqajstj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gaohongyu789.top/Article/details/gtjhtthhfc.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtwwlctddr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gttkjbzftb.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtpdjxvald.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtordslsbo.html

[R32] 参数个数校验
来源：http://dali.xuanzx.com/Article/details/gtmgvbwgwu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gthqdoheru.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtghvvkgfa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.dianchejie.cn/Article/details/gtraxnwkqb.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtavwcsopv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtwbxvrxps.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtofnbvbkz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jiagoushi.top/Article/details/gtirovnelr.html

[R36] 并发执行多个任务
来源：http://dali.gaohongyu789.top/Article/details/gteqpwofmh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zdqjudy.top/Article/details/gtxorarnhw.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtcjihfokw.html

files=$(ls -1)
来源：http://dali.svipenyu.cn/Article/details/gtufbeiobf.html

[R38] 管道串联
来源：http://dali.chenjidiqi.icu/Article/details/gtvkwtqydt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gtagiwdipa.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtldfepzvq.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gtvkdkeimf.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtmqvzzhiv.html

echo "log" >> out.log
来源：http://dali.jiagoushi.top/Article/details/gtacwxoeiw.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpiszdvuq.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtbowyuvmq.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtjzzckalo.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtwyxssjad.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gtwmfadlcx.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtxlmqswsz.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtjfeusdgv.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaimtryz.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtfbhhmwvr.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtikpwtnpt.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gttazuijjc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nwbrower.top/Article/details/gtshcffxlv.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gtphqtzmwp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtvpuicydd.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtadmgzbne.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtmhhuancb.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gtannjlfia.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtmqqlmncb.html

[R50] awk 求和
来源：http://dali.fengsongda.top/Article/details/gtnsfizatc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtszvvdzut.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcsirtyk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtshjlmzum.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gthewlrimx.html

wc -l a.txt
来源：http://dali.xylfe.cn/Article/details/gtqnljflqq.html

[R53] 查看文件头与实时尾
来源：http://dali.xylfe.cn/Article/details/gtmlhejsot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtvgltffyy.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gtoambdjnu.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtwxlsdxiy.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtvmhckmpt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtdlhelzsb.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtoxeogbux.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtdwnmtlyl.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtwizjosih.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtwivmgzyd.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtvabpsqhp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtqslpkftd.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobtuvszq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtiyrlqmle.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtlsqyjgwn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtwlmqqwgo.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtggapgysc.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gthzhqluim.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtknkuoodm.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtzeddmgym.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gtrnqzufyi.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxuanxn.top/Article/details/gttmoutvro.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtfuegkuev.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtkplphaid.html

[R65] 查看端口占用
来源：http://dali.iojbl.cn/Article/details/gtuucifrhq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtdfckvyhq.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtzdgjmhsn.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtngxnkzem.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gthxczhtwm.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtmxasgbgw.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtaaqraryo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xziqi.cn/Article/details/gthuogbznm.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtmmixqllb.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtohiqpxtz.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtillagaoi.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtavdvnshb.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtuszlyqtz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtgfybifyh.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtoqorpgby.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtihgaubid.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtvrqdtjsp.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gttbbqejfv.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtgrflurzv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cqqwz.cn/Article/details/gtbhlxatfa.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtdtsqyksq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.haohaochexian.top/Article/details/gtapilojga.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtrhbilmmy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtdaxnpmih.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtbjrsxfgf.html

read -rp "请输入: " ans
来源：http://dali.daria6918.cn/Article/details/gtdfvejjbv.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtnelgfxnu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.svipenyu.cn/Article/details/gtyscwxnfw.html

[R79] 解析命令行选项
来源：http://dali.yangfankeji.com/Article/details/gtjmhwgrsc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtvraqtigk.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gtydoagger.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtwdmpoqwg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwabhcnc.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtynvqmknh.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttsojzbcz.html

[S01] C：Hello World
来源：http://dali.yj20258888.top/Article/details/gtxfbntscu.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtrfnhrdhb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebexsckn.html

[S02] C：变量与格式化输出
来源：http://dali.snrcjt.cn/Article/details/gtnznjfihc.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtwcmxvxao.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtmdnjmfsr.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtanfkkkfl.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjtfndgs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtsnujwejt.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gterulgzxf.html

strlen(s)
来源：http://dali.tian-w.cn/Article/details/gtutgndrax.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gttrlqtezq.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtxbnymdab.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtkfpdnkhz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gthxtdqofl.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtwgatnmgl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtuvhhanzh.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtfmpfhzza.html


<!-- 参考信息 -->