代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gteukwhspa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtvxgvzdqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtzklveufa.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtvcnoskqy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gtlizdehuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtymggigol.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtyazzhkxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258.top/Article/details/gtcvhudnns.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtkjvhpiou.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtfojpzroj.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtyebtikeo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtgkgjkpjt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gthepistaz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtwoqhkrbk.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtbcuaqkue.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtujjejxph.html

[Q48] CTE 公用表表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdqlnmzw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtrjaqqevj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gtufyvdgub.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtkahullzz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtxsllppse.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmbhclcf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtypddqvfz.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gtnvxekzrx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtlqvwfqhp.html

[Q52] 删除指定行
来源：http://dali.sweek.top/Article/details/gtbgyrbuoc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gtlfmtgwvu.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtklbcckmq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtjekcxtme.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gtsqtiaswj.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtfgjfvfec.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtvctyyyxx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtsgszgfva.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtkalnngmr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfuljcwn.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gtsjgitqty.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtvljtkofa.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtiuuzzfnn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtgaphgwsl.html

[Q59] 分组内累计
来源：http://dali.hongshengwenyu.top/Article/details/gtylbsyhia.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtissznypb.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnntwwmj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtukfmhycx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtwajwbgqo.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gtrdhadnmf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtvmdrftmg.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtvrsxyhkg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtyqjeqjdl.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtzgprkfkc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtwlivcvnp.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtenqimbei.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtyzyaatde.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtkelysymc.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtrslsdqrk.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtgdeacbjy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sysykeji.top/Article/details/gtkjctpnim.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtvtlpxgax.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtorsawhca.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtdluwhxxl.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtxwjfkvul.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtvpeckkaf.html

[Q69] 查看执行计划
来源：http://dali.daxiang520.top/Article/details/gtugpowgmz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtkxvdhxat.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnjphmmf.html

ANALYZE TABLE users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzwyxljy.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gthtmdyklu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtewajohxe.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtdhutbfjc.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtwaftowdk.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtbulzmsar.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtfwfbpbou.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbkejghs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtfgyotvlo.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtzxdcbprl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtjehikpmq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gtsyorgrpo.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtfpmboidq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtrqdgslgb.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtjrgkgktf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtydnctlkg.html

[Q78] 当前时间
来源：http://dali.gogol.net.cn/Article/details/gtsqqmkkou.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtfrtsbhdn.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gtftdntxdw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gtihajpixi.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gthszumcyu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtknxeyniu.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtdhutsvof.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtjzwlrkqe.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtoindkjzq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gthgfrrpmo.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtttpzhiwg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtrcarkitk.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gtuvalotnn.html

SELECT TRIM(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtyoabqbnn.html

[Q85] 数值取整
来源：http://dali.xziqi.cn/Article/details/gtrcqubmpe.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtmgnhjuyj.html

[Q86] 读取 JSON 字段
来源：http://dali.sxryk.cn/Article/details/gtojnhuxbz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gttyfguhzy.html

[Q87] JSON 字段做条件
来源：http://dali.svipenyu.cn/Article/details/gtxrfqjuwo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gteeogoqzb.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtrsnpkyzd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtvalnlyql.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbmipnywb.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtmassvsgg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gttywqadub.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gtwosvfjdo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gttzeghuty.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlsuvtbzp.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjverunog.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyrbiawfv.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtzeidzckh.html

#!/usr/bin/env bash
来源：http://dali.zhengqikj.top/Article/details/gtbykxxkge.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtpvjejjjz.html

[R02] 变量赋值与使用
来源：http://dali.yuxming.cn/Article/details/gtqhrqozvu.html

name="Tom"; echo "$name"
来源：http://dali.zhongyouzk.top/Article/details/gtfmnkymsz.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gttvwcqzkp.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtjcjjqnkm.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtfqctiooq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtxionsszi.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtqpzbkydt.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gtwkeaofue.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtjltieofa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gttvriuwfs.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtsjlncxay.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtmdtlqzuy.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gtzjfzhorl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cdnleiting.top/Article/details/gtuvztioeg.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtfsuygcms.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtzktpfbql.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtxxoycqrp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtrjdgoguw.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtbngcqdmp.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtknrgrlfs.html

start) echo "启动" ;;
来源：http://dali.meibo888.top/Article/details/gtknuozqgi.html

stop)  echo "停止" ;;
来源：http://dali.xylfe.cn/Article/details/gtrooxhrby.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtyctugcax.html

esac
来源：http://dali.wangshuangyany.cn/Article/details/gtddudbkmx.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtcczdoykd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtvilzmltb.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtudndforj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtsubnqbbi.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtrjlfqskh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yvedp.cn/Article/details/gtlhncwqdi.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtatwggfxc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtpdqvoyfa.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtoidmqofa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtpgjqumor.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtplkigksq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtoonfvlin.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtampfsoet.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtukwqizsy.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtdvexlfqu.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtablxxfkc.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtjkbnyymb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtvdstanze.html

[R21] 字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtrobxiubi.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gtkpgqmkpj.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtlmenqsgn.html

echo "${s:0:5}"
来源：http://dali.nanxuanxn.top/Article/details/gtmqggsjoj.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtdgshysog.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtpzwvpxle.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtobpnfcyg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gtatkuucvz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinqigfzy.top/Article/details/gtvmyyjsao.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtocawuhye.html

[R26] 命令替换
来源：http://dali.daria6918.cn/Article/details/gtlghvazzq.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gtfydnlbww.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtabgrvhtn.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258.top/Article/details/gtqlsgxrzo.html

[R28] 浮点运算
来源：http://dali.hnqzz.top/Article/details/gtbziyqmzd.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqdsxtgp.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtaoquwnfk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtfjpoeinw.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtvbjjvmop.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangshuangyany.cn/Article/details/gtqgsdhjol.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtfcesjctf.html

f() { local x=1; echo "$x"; }
来源：http://dali.mhx1999.top/Article/details/gtgcdzyynx.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gtrvbwyvyl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtthwdqzgs.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtadzssmsb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gtgdgoedxq.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtcphpyybn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtlwlufykc.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gtfdypmwxg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtgimtvmta.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtgrtzxywl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtylkiothg.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtfdoshocf.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtnqxbzcpu.html

[R38] 管道串联
来源：http://dali.jlsjyb.cn/Article/details/gtxwcwviqt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtaegyjsfj.html

[R39] 重定向标准输出与错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfenijxas.html

cmd > out.log 2>&1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbblkxaye.html

[R40] 追加写日志
来源：http://dali.zdqjudy.top/Article/details/gtqzqvciib.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gthiromtzn.html

[R41] 丢弃输出
来源：http://dali.guowangkeji.top/Article/details/gtfwessdzg.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtyxaeduov.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtnhdtbxyq.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtouesnqmm.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gtppwzsgrb.html

find . -name "*.log" -type f
来源：http://dali.sweek.top/Article/details/gtrjhdfkau.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gtswtrfsij.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtlsfonoxj.html

[R45] 批量删除
来源：http://dali.snrcjt.cn/Article/details/gtamzmjgcr.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gtkhxbbtqo.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtuhxpwfkv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtbljjdqcn.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzbzqvul.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtrdmiekpy.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gttnxuiusw.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtxsqtiokz.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gthaaxmjia.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gtuhkybhap.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqexzbyny.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtqhkqpneg.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtyxrfibko.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtygnwnmrk.html

[R52] 统计行数
来源：http://dali.xuetiantiany.cn/Article/details/gtymbcnbee.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtywdxvbpp.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtvwhovktt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtydqojlbg.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gttbjnfhqv.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtoodkyyrf.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gtwvdebpsu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtwimgytoi.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gtbgttbrsu.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtnwmvpwqd.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtmipbirkb.html

ssh user@host 'uptime'
来源：http://dali.wangshuangyany.cn/Article/details/gtxthnossg.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtzzhqacco.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtcpuxgbnv.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtzhuojdlh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtehnmqjmd.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtscxrposv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtvoctumls.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxysuhto.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtrqxsyggb.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtscxrotcu.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtpfstnugz.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gtlwusexdj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhixingplan.top/Article/details/gtjtnunwfr.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gtrlgoquzc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gtnuyomhcl.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtvskavije.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ydzc1.top/Article/details/gtjyiryhxt.html

[R66] 定时任务
来源：http://dali.tanke756.top/Article/details/gtzwkitybz.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtksajneda.html

[R67] 生成随机十六进制串
来源：http://dali.ppjwa.cn/Article/details/gtlzhhilos.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtyvcskkxq.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtjtqcujkv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvtntdtq.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtuvjrfqho.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtkigkqxso.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtewcstwpb.html

date +%s;  date -d @1700000000
来源：http://dali.sxryk.cn/Article/details/gtnovzodys.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtcrxjvamj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtkpmsijwz.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gtabmrogye.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdkrqhdr.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtdtpxvfur.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtnabsghro.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtnvlvdixy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtfzwlxhgo.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtjhccobel.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daxiang520.top/Article/details/gteghbfblz.html

[R76] 使用临时文件
来源：http://dali.sysykeji.top/Article/details/gthxutuoke.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gttijffavw.html

[R77] 读取用户输入
来源：http://dali.xuetiantiany.cn/Article/details/gtixwolxes.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtochossag.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuifgvjw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sufxvd.cn/Article/details/gtlxksxqrf.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtdyahdnmh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtsxqgohoj.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gttailhdep.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtngttqsgs.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtsdnilkva.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtwugcxxir.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsufaezrg.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gthzctjage.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gtxbsolhcm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtsqmbopdi.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtpmxhuste.html

int a = 10; printf("%d\n", a);
来源：http://dali.yanxiufei.cn/Article/details/gtirpuaixg.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtpzepomtn.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgnlrwzn.html

[S04] C：字符串复制
来源：http://dali.daxiang520.top/Article/details/gtdrvyqosf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zycfv.cn/Article/details/gtavgkawfs.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtqcuxknwh.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcflnpzdp.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtouvnwtrf.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gtjhuzhcrt.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtmavxnosm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtzgctmuqr.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxuanxn.top/Article/details/gtlfdjsyvg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzptftax.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtqgahndwu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtnnauqzjv.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gtvisroqot.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtgdyfhjed.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtwtxitwut.html


<!-- 参考信息 -->