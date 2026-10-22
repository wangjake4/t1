代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gt2ojyfvmdj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2lyabzwsi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gt2rwviuidn.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2fmyzntfd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gt2edgytcsp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gt2vwzsuaym.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2ojzdamgy.html

[Q42] 连接条件附加过滤
来源：http://dali.guowangkeji.top/Article/details/gt2nkernrcj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gt2tieqhnjt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gt2vugpkzky.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2annsespm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gt2pppsutnj.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqbqnycp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gt2foipzpja.html

[Q45] EXISTS 判断存在
来源：http://dali.yuxming.cn/Article/details/gt2bhpwghcl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2wagihygm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2xidfurxn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gt2rkvskdad.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2hfxvhfdz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gt2yzzhbzgj.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gt2nqdoyccj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gt2aykcqyoz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gt2arkgoqzc.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gt2pgbfftdd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2okrehepd.html

[Q50] 批量更新
来源：http://dali.dianchejie.cn/Article/details/gt2xagbjpia.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2mcukxbsl.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gt2avqfveza.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258.top/Article/details/gt2vfvjxzdb.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gt2pclxriph.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2oftgedds.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2jzdbdvrs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gt2yotyxrsm.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gt2ismknkwi.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2lipreqer.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gt2qmffaicv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gt2cdhktujb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gt2duqliltf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2jgbvdnxh.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2rgvgzsrx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2vkfrjumm.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gt2kjncfphy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2esnrpguy.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wsfwrszt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cetztopb.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gt2jpnrxjba.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gt2dnrxrrqs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2zoejqwga.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbrdqiu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2tstvzrae.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gt2glspokja.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdmbsyuw.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gt2qxfexshe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sxryk.cn/Article/details/gt2dbvkayxn.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxzehgks.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gt2pmxdlavm.html

[Q65] 回滚事务
来源：http://dali.svipenyu.cn/Article/details/gt2wsisusxb.html

ROLLBACK;
来源：http://dali.svipenyu.cn/Article/details/gt2bkpulkfl.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gt2ugugadbh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gt2vlnsctpt.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gt2nifwrdbv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2fdpcruap.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gt2yrcgkufe.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gt2aodlytau.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gt2xvrvbasv.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gt2tfgztbqf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2lvtxqxvs.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gt2gjofjaey.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gt2xtluztev.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gt2zmybmilw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2afvlqynv.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gt2vqzncsgn.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2xaqxgcgd.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gt2glaqwpui.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oqolhvbd.html

[Q74] 强制使用索引
来源：http://dali.hfpthk.cn/Article/details/gt2arjghiik.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gt2lqqmraor.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2vqweoavg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2xpnefgiw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gt2niqtfwjb.html

[Q76] 按天统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmbuiatb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gt2iuxwedhk.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smjeompl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gt2nzhomghl.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gt2rcbgdyuo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gt2ixvykxoc.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2lmtggpxm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2bvihibjg.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gt2lrehzuer.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2pfmzwlcd.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gt2xbhsevvd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2aidzjmgp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gt2sxqgjlsf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2plvfhwot.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2najworjr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2jzftbjmh.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gt2hcdvparq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2rdesajob.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gt2evvilsxj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuanzhike.top/Article/details/gt2mtdkhpbn.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gt2gfzchskn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2pbcumzwd.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gt2wviffrsr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gt2xeqwrwgw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gt2ainljmfa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gt2xbefhnyh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2rtipfjsz.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2rptszuzz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gt2bpphncvl.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gt2uxqtvyqr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gt2siwizeeo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2okyuobmb.html

R. Bash 专题
来源：http://dali.yvedp.cn/Article/details/gt2xtqcwsto.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2pknjhzfs.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2akmcwgww.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gt2aukigyds.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yepyrokw.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gt2wbntgcdo.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gt2yxkyhnym.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gt2pkosadtb.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gt2ojggwezc.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsdcbbgd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gt2rtwgmyvn.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2tbhnsbiw.html

name="${1:-default}"
来源：http://dali.cucudq.cn/Article/details/gt2ryytngfb.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2kxyivedq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gt2acphxyiu.html

[R07] if 判断文件
来源：http://dali.chenlongwang.top/Article/details/gt2cijmgqsn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gt2adfgjibm.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmoqilry.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2ppnienot.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gt2dnhxxxyf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gt2csbufkgq.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gt2mqqbbzmi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2qhnuauzs.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adqzduub.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gt2sdjirnfj.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2jqihukbx.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2vyyhyhgi.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gt2ffibqzmm.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uplpuuwo.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2kidecrzs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2zxioigjc.html

[R13] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2soqvrwam.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2pvicedos.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gt2ouhljqty.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2obuhgxwf.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkbqexwb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncqvyfav.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gt2ygrubhvt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2dhxxfokt.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gt2wtscjtuc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgfzy.top/Article/details/gt2uusedsie.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzobqiib.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2uezuwyjf.html

[R19] 数组长度
来源：http://dali.gaohongyu789.top/Article/details/gt2jyipkhuw.html

echo "${#arr[@]}"
来源：http://dali.jqgfzy.top/Article/details/gt2bzmrnjxh.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2vhiwpfko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gt2pszjjuyr.html

[R21] 字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2pkjxqumk.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2lztjdtfh.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gt2xgeskyne.html

echo "${s:0:5}"
来源：http://dali.andypj.xyz/Article/details/gt2bboisvku.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2ozbmolvp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.haohaochexian.top/Article/details/gt2iqvjkpuu.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2txljfdmn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2tllkdijm.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuwwyzoa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gt2qvkineyu.html

[R26] 命令替换
来源：http://dali.shuidangran.top/Article/details/gt2nqhvezcd.html

now=$(date +%F); echo "$now"
来源：http://dali.nwbrower.top/Article/details/gt2pewrqnms.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2jbechbzi.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gt2slyhrqyd.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2vqmsetcv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gt2dorzzijl.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2syzeqpua.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gt2mzwrrrfu.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gt2rgoxqrgv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.fengsongda.top/Article/details/gt2zayeqkbf.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gt2tqwlguno.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gt2rhzjxxpt.html

[R32] 参数个数校验
来源：http://dali.aibaodan.cn/Article/details/gt2pnsxukhe.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2coujtbvg.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gt2jvvsajoz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gt2nrvkskro.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gt2mipdxfih.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2txwwzroa.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2vpbwfbmw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.smart0.xyz/Article/details/gt2zuswxjif.html

[R36] 并发执行多个任务
来源：http://dali.yanxiufei.cn/Article/details/gt2nkfpeypm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gt2rtwljfim.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2vxxealvl.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2ycrupzrn.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gt2slakvnmw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.meibo888.top/Article/details/gt2rjrdlqrz.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2rijdxiie.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2axmmdbee.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gt2yjprcpsr.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gt2ejsadtbo.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2rtzwknfs.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gt2upnkwwxm.html

[R42] 输入重定向
来源：http://dali.jiagoushi.top/Article/details/gt2azfvuxax.html

wc -l < a.txt
来源：http://dali.andypj.xyz/Article/details/gt2apqeczoy.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gt2xxmvbano.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gt2qfsjqtii.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifabkmhb.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mindoehk.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2qnkqwqef.html

find . -name "*.tmp" -delete
来源：http://dali.cdnleiting.top/Article/details/gt2gibygdgq.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gt2bbxhsetp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gt2cnbsskqk.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gt2rnfwlvqd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hywenlv.cn/Article/details/gt2cukcsqiq.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2htzmkfyg.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gt2imcjkrbx.html

[R49] awk 带条件
来源：http://dali.chenzaomai.com/Article/details/gt2qqxszpqa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gt2pblszimd.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gt2cabwaxyh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2umhxyoeo.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gt2zhahejfp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gt2avsaioiv.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gt2hecfzofj.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gt2rxkwfuvc.html

[R53] 查看文件头与实时尾
来源：http://dali.fzhhl.top/Article/details/gt2ctzzgqgx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gt2kpldbhwg.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psvfpfte.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gt2jxwpqzkz.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gt2slouctop.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlggpvoh.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2mnymaqbd.html

scp file user@host:/path/
来源：http://dali.yueranfly.top/Article/details/gt2wbcgking.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gt2uvdivbdf.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2irkllmfn.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gt2natwsfaa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2fpihaqga.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2xircfamd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gt2ltkrrwbf.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gt2zdkkmkbh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgufenzy.top/Article/details/gt2bgimcowe.html

[R61] 磁盘占用
来源：http://dali.yj20258888.top/Article/details/gt2thtqkilw.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gt2xujloiil.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gt2nsernmsx.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gt2omnefupj.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2eabgszdp.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2zkdwkumf.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2vbopxuwy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gt2spfxbcas.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gt2brxycjvk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gt2ifspjvit.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2zcmnpowp.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kijhqfme.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gt2ggetdcen.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gt2tdpeqwth.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gt2dhphrkzy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2knetyydl.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gt2bmpiijlq.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2gjnpconl.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gt2mqarbynk.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gt2skybibpt.html

[R71] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gt2ddbhgxpl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guowangkeji.top/Article/details/gt2vorqmyyn.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gt2seyxnary.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2jewgopbf.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gt2svwjpvgc.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gt2cmplzysx.html

[R74] 批量重命名
来源：http://dali.tianlin.xyz/Article/details/gt2ojwmogpd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2uklvczol.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2gfymilzo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gt2ncwluliu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2areabkja.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gt2vvuefzfy.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gt2zdzrejqu.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owxwdnpd.html

[R78] 交互式菜单
来源：http://dali.sysykeji.top/Article/details/gt2neyqykng.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2kghebxwi.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2buqkjhyf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uumqgxlg.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gt2stiztwyw.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gt2xeptjlrw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2tyklweqo.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzdzysyx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2vdeooaco.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gt2mtkgfheb.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2sbxnlyeg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.316326.xyz/Article/details/gt2euwajpap.html

[S02] C：变量与格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2yrcuoatp.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxuanxn.top/Article/details/gt2ymlscmjc.html

[S03] C：读入整数
来源：http://dali.zdqjudy.top/Article/details/gt2myidouqu.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gt2xnjunfay.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gt2ngmscjck.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqwzqkoz.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ialymfru.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gt2jeffjqbx.html

[S06] C：字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2rnhnpmsm.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gt2cwyaueex.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gt2fysqeucz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2mwpoopxs.html

[S08] C：动态内存分配与释放
来源：http://dali.shangyingyoupin.top/Article/details/gt2ucedasvm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dwbzsulv.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gt2fgkwmhsb.html


<!-- 参考信息 -->