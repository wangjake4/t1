代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2nlhgzwzp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gt2acebjxgh.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gt2hcqfglug.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.316326.xyz/Article/details/gt2lhtqtfpj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gt2ujlrfnby.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2powkyxut.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gt2ygoxvsrx.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gt2kjccowow.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjjhzebo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenzaomai.com/Article/details/gt2madxkewl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gt2wyvdfiba.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gt2xvigioxz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gt2hbuqcadx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2yiyxtdgn.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gt2tvjqfrho.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2rocgecaf.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gt2fvmebdzf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gt2veqxyyms.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2wogofvan.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gt2utcdkxnt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsqumnmh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hywenlv.cn/Article/details/gt2rflpjmis.html

[Q47] 与平均值比较
来源：http://dali.316326.xyz/Article/details/gt2lkrlctqv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigufen.top/Article/details/gt2pemtqfdo.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gt2xqblylua.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daxiang520.top/Article/details/gt2yjqyvehj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gt2niivznth.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gt2djquvqgd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2ldrybnml.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gt2infuawdo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gt2bvgbvgsd.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gt2hrvogelx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvomktqf.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gt2fxvwtglv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gt2rqihbvez.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gt2rnnygcbc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2csqabvlh.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gt2opcocuvh.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gt2szajamte.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gt2cwommnpb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gt2wbrabaaw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2tdjitvms.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2qlhzdvhj.html

[Q57] 行号
来源：http://dali.zycfv.cn/Article/details/gt2vegslmtt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyjkeeld.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gt2nhjcgxdf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2srqzoiku.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2psotktwa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2uibdkmky.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gt2xbdjeuwo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gt2jzaiopim.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2lxwmggtd.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gt2qtgvymab.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2mcgisacn.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gt2qclngrsz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2kogtszog.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gt2uonvjvie.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gt2kuiaufhm.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gt2cwfmaexp.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gt2cgfwbomd.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gt2hmmsltop.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vjghpmcv.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gt2beiqsqwv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gt2kwboolvb.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gt2bkazeqxt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikwhtkag.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2hzxewuiu.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gt2cexcsxhk.html

ROLLBACK TO sp1;
来源：http://dali.ybcxt.top/Article/details/gt2wtjydddi.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gt2tivaioxd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gt2acmytuko.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gt2czdbhthc.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxihxlhy.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2zrkujwlk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gt2fvyfcwsh.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gt2wxcpixpz.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2glljqrsd.html

[Q73] 查看表状态
来源：http://dali.9152youxi.cn/Article/details/gt2bvsxejkg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yvedp.cn/Article/details/gt2qsbrarat.html

[Q74] 强制使用索引
来源：http://dali.chenzaomai.com/Article/details/gt2okfkphze.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gt2wldjoyhe.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2eoxbmnui.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2aglemumj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gt2dwrobjqa.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gt2ldnisobc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gt2suwnkqhd.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gt2fzidxdcq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gt2lhuqfycq.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2dbscxpbb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2emxdqkoe.html

[Q79] 字符串拼接
来源：http://dali.zycfv.cn/Article/details/gt2jlajpmbx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gt2nxoerenc.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gt2zmvjpgdc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2fklurxzx.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gt2otiqkhue.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xqhzxvae.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gt2mlvhjqko.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2izgxembp.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2caygwgqw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2oaqrzxnw.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gt2lfrofntw.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2bezavesi.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gt2qszdhqbx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2hdbnacpn.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gt2symhiymy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuanzhike.top/Article/details/gt2xdipwxkc.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnahdeta.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fengsongda.top/Article/details/gt2vskpeqnt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gt2plfrvycr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gt2gxtcmvnr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2umnccbip.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gt2caaxhtiy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2seohjekd.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gt2mbudkxdt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2qccdnzse.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2arzknokv.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gt2mfvxyldz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kpknuxyg.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gt2lqsqudbe.html

#!/usr/bin/env bash
来源：http://dali.chenlongwang.top/Article/details/gt2qyeceais.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gt2jbjkwuyy.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gt2ougniqua.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gt2kbozkvgg.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2oquopnyn.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gt2nowjvorc.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gt2lxbgdzql.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epaefrlq.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gt2ixvhhfll.html

name="${1:-default}"
来源：http://dali.yonumen.top/Article/details/gt2znihslsq.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gt2mjdwudry.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2whltohoh.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gt2wcyhlkrj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gt2cqysoinu.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gt2sycpvfii.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gt2takzploc.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2vxerelym.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2qvusager.html

[R10] 正则匹配
来源：http://dali.cashguo.top/Article/details/gt2cgtbcbze.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gt2xbddivpl.html

[R11] case 多分支
来源：http://dali.zhengqikj.top/Article/details/gt2lkdysjvs.html

case "$1" in
来源：http://dali.aibaodan.cn/Article/details/gt2zfpobfjp.html

start) echo "启动" ;;
来源：http://dali.yuanzhike.top/Article/details/gt2cxfyqofv.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gt2sfuuqciu.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gt2yghzbebz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfzjgwo.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2dtlskbmy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.meibo888.top/Article/details/gt2hppwwgbg.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2txefwpzv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2hlavxitw.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gt2nedenmwg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gt2ahbdmpai.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2awmmwbql.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.birdmap.top/Article/details/gt2caasivzt.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2mheyywaq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2pykshvax.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2yxbpgvti.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pdazycbx.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gt2ffnwwlcz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gt2pjijuprk.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gt2qpgktdls.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2onxxjfmo.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gt2kfadkoji.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2wydumxty.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpsqdtob.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fyzsimyf.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gt2qsjzqhxc.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2xsbsldzi.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2hnuwecjg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rleunazl.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2znzugeyj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2noifppzx.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gt2ubzslevw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gt2flxcecuz.html

[R26] 命令替换
来源：http://dali.dianchejie.cn/Article/details/gt2nzjiiedd.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2wabnqupu.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gt2ucvswfcs.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gt2xlcdfevj.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gt2jpglfoqj.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gt2pggvtnyr.html

[R29] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gt2klswgupj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gt2fmundaqr.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gt2kmwasisx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2iqfkopbs.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2zfjspxyd.html

f() { local x=1; echo "$x"; }
来源：http://dali.sufxvd.cn/Article/details/gt2enogehad.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gt2sdwvgdyk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gt2dfiojbql.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gt2qkfmejit.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenlongwang.top/Article/details/gt2tzdlhelg.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gt2pwxxftue.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gt2ilahsvqo.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2gvpkmzed.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dianchejie.cn/Article/details/gt2cefykiif.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gt2dcnrbuuy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gt2wihkpvip.html

[R37] 把输出赋给变量
来源：http://dali.wangdashe.top/Article/details/gt2uycnhafn.html

files=$(ls -1)
来源：http://dali.guowangkeji.top/Article/details/gt2qiqyfczn.html

[R38] 管道串联
来源：http://dali.sysykeji.top/Article/details/gt2ogiszzec.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shangyingyoupin.top/Article/details/gt2acpqqpzd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvnvynvy.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2lbtmxzmq.html

[R40] 追加写日志
来源：http://dali.daxiang520.top/Article/details/gt2potvrswu.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2rmrvelpb.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gt2kuzmoobn.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxtplkgc.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gt2pfnssxhc.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2hbjkewpb.html

[R43] 按名字查找文件
来源：http://dali.yueranfly.top/Article/details/gt2olmiyeri.html

find . -name "*.log" -type f
来源：http://dali.zhoulong.xyz/Article/details/gt2wheaousn.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2wpgqtqqq.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gt2bwbosloj.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gt2ovzynkdo.html

find . -name "*.tmp" -delete
来源：http://dali.dashuyun.cn/Article/details/gt2zfcqhbds.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sgwoilms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gt2mcmpqttb.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gt2pxqkhrfc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ipavoork.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gt2iwwasxtb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2lyggfkac.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gt2unycxtub.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2anpikgwq.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2vniziget.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2kjgkmtyr.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gt2fiwrnykv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gt2airnnlvj.html

[R52] 统计行数
来源：http://dali.fengsongda.top/Article/details/gt2xeelrnnh.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2ebmffzik.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gt2dhxuonnu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gt2zihtecbq.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjmxrycm.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gt2zekvehws.html

[R55] 压缩与解压
来源：http://dali.cucudq.cn/Article/details/gt2lictscbm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2yldityef.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvydazhl.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gt2bynhdqun.html

[R57] 远程执行命令
来源：http://dali.xuanzx.com/Article/details/gt2alctdhtb.html

ssh user@host 'uptime'
来源：http://dali.kuanghao11.cn/Article/details/gt2lhckvnwb.html

[R58] 下载文件
来源：http://dali.0kj1m.cn/Article/details/gt2rjhtvggc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gt2twfofxin.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2phwaiamf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gt2lfyflwjs.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2lpvgrmlk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2muotfulb.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2hyztbvsg.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gt2uhzyizit.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gt2yztagfdw.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gt2gzioxtbn.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gt2nmffdhao.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gt2iwggxito.html

[R64] 结束进程
来源：http://dali.ybcxt.top/Article/details/gt2lvszairj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2mcupuahp.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gt2sfbawtry.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.bjfxy.top/Article/details/gt2lqyaechp.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2sihqlqgf.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2claxedsa.html

[R67] 生成随机十六进制串
来源：http://dali.hywenlv.cn/Article/details/gt2gudpbszx.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gt2irkqyrlv.html

[R68] 计算文件校验值
来源：http://dali.cdnleiting.top/Article/details/gt2gebheozv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gt2rhgnaaqr.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gt2busyiwrq.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2mrsuvbbc.html

[R70] 时间戳与互转
来源：http://dali.kuanghao11.cn/Article/details/gt2spnjpztv.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gt2atqsqful.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2ileuxetx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2wwbtpbkr.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gt2geiqmnih.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2otgokiow.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gt2tbrpuofo.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2giqgawaj.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2xlauuxcl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2ihgyukif.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gt2txqjxpzy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2qyufabvb.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gt2rbukiaon.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gt2aonkdlha.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2xuwktych.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2olymlrpk.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2liyejrwy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gt2qhskwryt.html

[R79] 解析命令行选项
来源：http://dali.quarkkingdee.top/Article/details/gt2iodyylaa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axkmcuir.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gt2psjqpyxk.html

time ./run.sh
来源：http://dali.0kj1m.cn/Article/details/gt2budthfla.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2picsihtv.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2iucuktwn.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2uhlbqcfp.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2rknouzjl.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gt2hptcrshq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gt2xwgjreeg.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gt2xqmxpbwa.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gt2ezhnrdtt.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2xuibaoei.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gt2uimoczpx.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gt2oyxbomsj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2oupybufh.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgfcsbop.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gt2iqglkbai.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2ksktrgna.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onmtqntx.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gt2nhtwznyu.html


<!-- 参考信息 -->