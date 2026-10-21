代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtcrfqfruw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gtwhbcbklt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gtshshpoib.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwlwguac.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtkspahchf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtcwajqyqm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtqcpldbmq.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkbrvgav.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gtydnohwuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gteaolwqxf.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtxideiggp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtyiueepfl.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtfhkabsax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hywenlv.cn/Article/details/gtwiqincxr.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtxpcbcxqh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtddooyzdp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtzgtzpogi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtoqpjqbfa.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gtijorzpjy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtubxqxndl.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtqkuaokop.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtyhvycqgo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlwwgdzq.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gtzvwswqzs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtyouquhmd.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtopmwihsi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtxjqjelxc.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtoahhbzly.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtdrmqrkhu.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtnkxlivio.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtczhyvyge.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtdoeonzbb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtsomirdew.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gticqnoitn.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtkwwjvtwc.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxelsetdt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiplsdoa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtgvxnnjtj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gtxdkweayf.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtejtkqkgo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtsmhfjvby.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtgunokspt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtzvyhhtuw.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtpwqukaur.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtpospsaie.html

[Q60] 取上一行 / 下一行
来源：http://dali.jyoumei.cn/Article/details/gtkwjpswci.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtvedgsqeb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtordespiw.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtnhgnqebn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtaawbycub.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtwssyqprh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtgcykbyjh.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtkckbpmsl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtqdpebrcd.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuixocqaf.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtfjhriuyo.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtfnctszoo.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtiyuuwvni.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtbvwyihzu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtcxzffeod.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gthpcwrmnm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gthdweifft.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtgcfkzlpl.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtmnutkkzv.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gteyxzqxhe.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtacvmjyip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gtnmrkgmkl.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gttgceyztx.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtkxsjoyrp.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtslaihrmb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtkzyuigzp.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtncjawied.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpxqlirqq.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtvxrofvyl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gtxtnprhfr.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtjsdbmmwg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtxshhiqab.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtezlzfstp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtaonhjzav.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gticmxlwjo.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtrksssstn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gtanxuppcy.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtdybxuiuz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtjjkvhttj.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtghrunmid.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuxming.cn/Article/details/gthbdsjoty.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtydmjhhop.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gteafzworp.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtlpwemdvf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttopiivjk.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtwsgmmzuz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtodkaxreh.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtiqhzvhph.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtevelpqyk.html

[Q83] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtcglfblly.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtdwhszgcn.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gtuftilppm.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtklsyqpcd.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvwjkthk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yonumen.top/Article/details/gteouipika.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtugebukvf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gtqwrdqkdt.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtaubrwqrn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gthdysxkoc.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtjkmacqkw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtxhgjqmef.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtbbrkthzs.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gtdtfdokkd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtxjamaeii.html

[Q90] 生成序号列
来源：http://dali.shzxlz.cn/Article/details/gtuwkghapu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtwfsaelem.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfhyuiboo.html

R. Bash 专题
来源：http://dali.hnqzz.top/Article/details/gtotizgpzn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtufquayfh.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtyrqtcxtx.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtlsjbcfnv.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtjuibdaiu.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtgzyidegf.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtcscvyzkm.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtieugadix.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtistngjyb.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtgjqqolcp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtoomzokee.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtdkpsleuz.html

name="${1:-default}"
来源：http://dali.hammf.cn/Article/details/gtxjxmukti.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gtpzmxeyfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtlfykdbhb.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gthiubbkiu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gtozfdxbxt.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gtnzxzwbww.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtuyhdqwgi.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtycwtqesj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gtqoiakczq.html

[R10] 正则匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gthncvkaba.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtimvqutrs.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtqsmjwgac.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtfzjaxvcr.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtnvjvrmkt.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtltdefblv.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtwvbbkxzo.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtnianadlz.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtntcqmcgi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnxdzstu.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtzlwqtmrt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtjnutfvbp.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtccjmntrx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtmscxzppm.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtcdrlmoya.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gtoojkwbxo.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxczobyiz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtiafwunzi.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtmnfejytw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtldgdyfpa.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtiltuvabq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuanzx.com/Article/details/gtoxkweirp.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtityxtery.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtckwnchev.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtmwxzplfc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtivusbqtg.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gthttmtjli.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtgiyypuqq.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtuqrluizd.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtftipkfma.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtlghbxzer.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtlezvqtcd.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtaoobszsj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.feifeiyinyue.top/Article/details/gtnlntnidr.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtmithrfcj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gtobqjkzwd.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtwoxllglm.html

now=$(date +%F); echo "$now"
来源：http://dali.cucudq.cn/Article/details/gtwamrtoqq.html

[R27] 算术展开
来源：http://dali.hnqzz.top/Article/details/gtgtomamuj.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gtadbjwhkx.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gteimblfcq.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtimxqxead.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtfdisonli.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gterrdujmj.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtdcezflax.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtkfdadzxt.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtaybuayew.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtaddrwhin.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtwnlhnvle.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtkjtklpyp.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtvotwwckh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhaomingkeji.xyz/Article/details/gttedsftpl.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtrekygifq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtzdwsunop.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtygbhoesl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtmyqikrod.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtgrvfmmjx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtpiywwysh.html

[R37] 把输出赋给变量
来源：http://dali.redwolf501.top/Article/details/gttorlxqfg.html

files=$(ls -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxoavpkxh.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtroczrxxz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtdqzmkoep.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtynhvdcoh.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtuxjdpblx.html

[R40] 追加写日志
来源：http://dali.birdmap.top/Article/details/gtzfpcznpj.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gtjhoxrkaf.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtvbtinpwx.html

cmd >/dev/null 2>&1
来源：http://dali.yuxming.cn/Article/details/gttpausdxo.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtdsehpvox.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtaliorrss.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtnryhbubu.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtxmumszml.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtxdwlhnuq.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtkezuuopt.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gtazoeowri.html

find . -name "*.tmp" -delete
来源：http://dali.svipenyu.cn/Article/details/gtisgevydc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtalvnocfp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gtukhbkocf.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvvfcdrp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtkbwztvqy.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtzgsmwtdd.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjubvdfik.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtmooucyws.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtdckdawlv.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtlapxvhpy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtkffwcozc.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtkmfpkfzn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtwitxfpsu.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtpdjglegx.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjdsdmnw.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtnfypadcd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gteseuyije.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtwkhydghy.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtwwzfbpgi.html

[R55] 压缩与解压
来源：http://dali.nanxuanxn.top/Article/details/gtqugfimdl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuanzhike.top/Article/details/gtnobqcvsp.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtwbjgcnla.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtgczpawzw.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtvxlucque.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gthmalnetv.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gtdmmsmkzn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtvjsbtzru.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtdwgpekxa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtfcsihfam.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtfobeggwn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujniavax.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtwmakjyei.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gteevalxfz.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtaflltweh.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtntfyuozc.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtvzjkkuoy.html

free -h;  ps aux | grep nginx
来源：http://dali.nanxinkj.top/Article/details/gtjrfjimkf.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtycnqgdkb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtyszcyazc.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtdpntpaww.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtknyqxzyz.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlcwlmfk.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtpcbihexd.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtresqdjyk.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtgxlvghiw.html

[R68] 计算文件校验值
来源：http://dali.sufxvd.cn/Article/details/gtcozvtmdz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gterfshhzh.html

[R69] 生成随机密码
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhwbqqgd.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtlbpkgimn.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtwcbrytlf.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtsknwahtc.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtubxgrkby.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtduhxijnc.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtlizandrs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtoynsiykz.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtuveynqgk.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtbwjqganr.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gtkfantkht.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiagspjc.html

[R75] 导出环境变量
来源：http://dali.hnqzz.top/Article/details/gtuplzrcwt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gthzoxadar.html

[R76] 使用临时文件
来源：http://dali.zhongyouzk.top/Article/details/gtsnuslxdc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtypqbrvjm.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gtwgnuhyxi.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtvncjoxpk.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gthhjteswz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gtigwxxalu.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbpehebx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtpdxpdfyk.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtbiymvdxj.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtovtkpezb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxijgigju.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtfzixmscg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdefjxlue.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtwhkmvrlx.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtagmexbwl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtfdwolzsh.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtbnoumdbi.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtgofjyksn.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtmvltgliw.html

int x; scanf("%d", &x);
来源：http://dali.sufxvd.cn/Article/details/gtvyhhkafq.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpkntang.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sxryk.cn/Article/details/gtbzsuzphq.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtfvkeqqtt.html

strlen(s)
来源：http://dali.mhx1999.top/Article/details/gtozyrprtf.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gttaqyvfna.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gtulhrtifg.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtzepkbehj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtkjfztsth.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtgqaqhbyz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtbkvuzqog.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtblzbkpeg.html


<!-- 参考信息 -->