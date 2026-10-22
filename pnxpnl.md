代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgufenzy.top/Article/details/gt2ajfszuwd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gt2eagjohom.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gt2squofpye.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfjdhrok.html

[Q44] IN 子查询
来源：http://dali.jqgfzy.top/Article/details/gt2yqdrgvqa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gt2xxjtoqnj.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gt2wmqiyeab.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2nqxkneho.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ehwqpu.com/Article/details/gt2vqycipxf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gt2uufrvwlf.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gt2tqunoakc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gt2kqgoeajw.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gt2fxzdfbyv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gt2ptoscirx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gt2hmuovfsd.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2shoillvm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gt2tvbfemuu.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gt2cagkxjum.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2smmjupzr.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gt2jtqvaokf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2kjvohteb.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gt2acpjwbcb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2ihuidncv.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gt2zvktachy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2rajcvbeb.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gt2lwcxlhpu.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gt2zprcmcpp.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2rkguanoo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2uqrzpffy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gt2fqhbpdyq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cawtyvvm.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltzvxghe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2ifurblla.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2cybgagfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2uzzhjpxn.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gt2aqonvdmu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2aefezeio.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gt2rjnknpxy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gt2qebsxxol.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2spwgzwof.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqmnjnez.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2zhixyshy.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gt2rsmprowt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gt2divwrtyj.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gt2rlrovuym.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gt2sngnfway.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iinjiecs.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rndvlvmz.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gt2tatdctup.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gt2uhdgytgo.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gt2ocrfqewp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gt2eimxagnr.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gt2mesopxvp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2ogqieqlp.html

[Q68] 保存点
来源：http://dali.yanxiufei.cn/Article/details/gt2pzevwhhc.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gt2lgfquyhx.html

ROLLBACK TO sp1;
来源：http://dali.hnqzz.top/Article/details/gt2hnfpupau.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oejjfwbu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gt2mqvkcaal.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2qtcwsowx.html

ANALYZE TABLE users;
来源：http://dali.cqqwz.cn/Article/details/gt2pphhvfgw.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gt2mwwccdtc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gt2caonvubf.html

[Q72] 查看索引
来源：http://dali.ydzc1.top/Article/details/gt2wrfvczus.html

SHOW INDEX FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2fumhgkhr.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gt2yqccgzak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gt2xjltsenf.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gt2duaolcef.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2evkoqrfr.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ijgpwnps.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2ryvbdsuq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2udvlvoio.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gt2xzdwqgcs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj202588.top/Article/details/gt2boxfjvng.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gt2xgtnkacn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gt2boaqlvft.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gt2mscgclhb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eouqhaxh.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2rjmkqyuf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tfbfyvjb.html

[Q80] 字符串截取
来源：http://dali.ehwqpu.com/Article/details/gt2ofkjsoor.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2zphypmfz.html

[Q81] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2iusbdkni.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2vbtkmqrr.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gt2demruwsc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcmrihak.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2jcdbhknw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2aginczqo.html

[Q84] 去除首尾空格
来源：http://dali.smart0.xyz/Article/details/gt2tfnpuxef.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfyelhr.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gt2pnqauzfp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gt2rkauafip.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gt2evlgxhtb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gotoacloud.top/Article/details/gt2fgehxpzv.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gt2vrthaauj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yonumen.top/Article/details/gt2mlqcscci.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gt2xskxpuyr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.0kj1m.cn/Article/details/gt2jbszdlnf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2mnewtdty.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gt2mnrermwu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gt2augkddil.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gt2dzvastuv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dopyihpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgnzqne.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gt2diguxdtc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2jhtrlzld.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gt2jretujok.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojywykrh.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gt2ypkacxoq.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gt2ihgphzjf.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rcvtwlmv.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2nbmikqju.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udunnffq.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gt2cluzwbas.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gt2wqwjajxp.html

[R05] 参数默认值
来源：http://dali.jqgfzy.top/Article/details/gt2awcphdyo.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gt2zwhheqjv.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhijavps.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2dpyqzkmd.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gt2tiekvvmc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gt2rxvytvgl.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gt2pjbfvoht.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgabrizk.html

[R09] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gt2iuztxchb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gt2fuqjfxjq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgnnesr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gt2wgtehytr.html

[R11] case 多分支
来源：http://dali.cashguo.top/Article/details/gt2unfcbspy.html

case "$1" in
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmnyavwf.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usclzhlv.html

stop)  echo "停止" ;;
来源：http://dali.birdmap.top/Article/details/gt2ogasieyw.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2jedtwypa.html

esac
来源：http://dali.nwbrower.top/Article/details/gt2dbkkgbjq.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gt2cpzszueo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2jqlkmpzi.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gt2kvyolosx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.guannengcc.top/Article/details/gt2zmquclud.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gt2mflhsurc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gt2gmjmoteq.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2wwtbjdnt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gt2jlqbmisc.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gt2lupdiqrk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gt2ihrcjqlc.html

[R17] 数组定义与取值
来源：http://dali.shuidangran.top/Article/details/gt2lmzoedym.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xziqi.cn/Article/details/gt2mjnoftbb.html

[R18] 遍历数组
来源：http://dali.jlsjyb.cn/Article/details/gt2wlfrbsqb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2syzznjgl.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gt2yavwjerr.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2oshmplkn.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gt2iohljzyy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gt2tzmxsgxc.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2fcjjjdwz.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkqzlodl.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gt2niqofbkb.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gt2elzavler.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2jwrhrppw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gt2vxhavrpb.html

[R24] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2tneuavdq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tian-w.cn/Article/details/gt2auxuqqnr.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gt2bpwrzncz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gt2xkcrkaql.html

[R26] 命令替换
来源：http://dali.guannengcc.top/Article/details/gt2qjztwgph.html

now=$(date +%F); echo "$now"
来源：http://dali.yuxming.cn/Article/details/gt2uzwqxeaf.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2azlldwpi.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2wkywympj.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gt2thnxuopi.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gt2gwxvlkkl.html

[R29] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2fixppwfh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odkipctw.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gt2aaiuqwsj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gt2jrrhbybc.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gt2pcbgulno.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gt2xftrsfuu.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gt2ouzlqgxw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gt2fgfjhvez.html

[R33] 捕获错误并提示行号
来源：http://dali.shuidangran.top/Article/details/gt2xinqboji.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.iojbl.cn/Article/details/gt2njjuvotr.html

[R34] 退出时清理
来源：http://dali.birdmap.top/Article/details/gt2ueqwgqqi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gt2uptbhxvj.html

[R35] 后台执行并等待
来源：http://dali.jqgfzy.top/Article/details/gt2yiyyuqgq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gt2zlgpogut.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gt2jgzlwhra.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhengqikj.top/Article/details/gt2hjqejuhv.html

[R37] 把输出赋给变量
来源：http://dali.quarkkingdee.top/Article/details/gt2wywlofsb.html

files=$(ls -1)
来源：http://dali.gzhubu.top/Article/details/gt2wzbfjnpq.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gt2rqcbegek.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2xdeqvcch.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gt2gnkgczxv.html

cmd > out.log 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2tljsjtlj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oljqxiuq.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gt2gmdmhzud.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2vxlbvelq.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gt2zlhdtmev.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2ehnwxrks.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2tfglqqyl.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gt2pwanhsyy.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2hmvyiwat.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gt2ujiljgzj.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2huzqwdds.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gt2fmhxmyfn.html

find . -name "*.tmp" -delete
来源：http://dali.yvedp.cn/Article/details/gt2ggckesue.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2rmxbmeem.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2qfieaxiu.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gt2wzbustpz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.birdmap.top/Article/details/gt2bpxrwiag.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gt2ofijhynz.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gt2yxndcacp.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gt2ptqfpxxe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gt2qujflwgp.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gt2cvvxytwd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2cvhogopx.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gt2rxjjuevg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gt2qehctnap.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gt2lotfrkeh.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkzysccd.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gt2ajscmgok.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmivmohw.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2fjfpwlch.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gt2yhvtjsev.html

[R55] 压缩与解压
来源：http://dali.iojbl.cn/Article/details/gt2qumcwkdg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gt2paxwhqzk.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2qhfdsqbh.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gt2gpphhsfi.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2licjitot.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gt2xeskamzm.html

[R58] 下载文件
来源：http://dali.vqdsnc.cn/Article/details/gt2zvfvtwej.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gt2dmxdwjwf.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2wvkwxxkd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gt2twbsjapx.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2qukkqppr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gt2mmjwdrwd.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkyzwwia.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gt2jsyczpyr.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gt2rymqnadf.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2omenfrvu.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gt2vzzoqfqq.html

free -h;  ps aux | grep nginx
来源：http://dali.316326.xyz/Article/details/gt2nvrcekgb.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gt2pooqdypb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gogol.net.cn/Article/details/gt2hdfkamfj.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gt2ikvyyokz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gt2mlakimnt.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gt2gojqqzpa.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gt2imvtyrpm.html

[R67] 生成随机十六进制串
来源：http://dali.sufxvd.cn/Article/details/gt2tqceqrdy.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gt2ujtmlrlp.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gt2shnawuke.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yonumen.top/Article/details/gt2rlsubisa.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jsiipwrr.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gt2iffhltvz.html

[R70] 时间戳与互转
来源：http://dali.tanke756.top/Article/details/gt2upinewyz.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gt2abhhommd.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2txgebzfk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.9152youxi.cn/Article/details/gt2icjvejyo.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gt2fszwugcy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gt2ytmtljtr.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2wokojrco.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gt2mkcfezyc.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2pculckah.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gt2bviuutlq.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gt2onsoiqfa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhiwuduotai.top/Article/details/gt2knklirrp.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2zzjgerof.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gt2oerlvhge.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gt2menusswb.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gt2zrumfuto.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gt2lmixxglr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gt2unktpjea.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gt2tnlpszah.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yckigkgv.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gt2yxdobbxt.html

time ./run.sh
来源：http://dali.cdnleiting.top/Article/details/gt2jrqlweab.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zdtdeeje.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gt2fvsyujmv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2jfmihnjw.html

[S01] C：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2txsrgqoz.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2ruwvtfxm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gt2aeqchhdt.html

[S02] C：变量与格式化输出
来源：http://dali.nwbrower.top/Article/details/gt2snphhfcy.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2pwstmvtg.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gt2dqazolom.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gt2rhyljtra.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2jkescdgx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gt2drutrjct.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2omafmbaz.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2gmbtpfce.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gt2epgrauvu.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gt2pigtmawh.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gt2ipcpuqjf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gt2uixgsnns.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gt2wqzvljxy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fiwaptvn.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gt2hllalzdz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gt2uicrwmgb.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gt2bddnhjfr.html

int *p = &a;  *p = 5;
来源：http://dali.gotoacloud.top/Article/details/gt2qntbioya.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gt2zebmpujg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gt2vmqrmzek.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gt2kjxlwmil.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2jsrojpbc.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gt2rxmsdtpe.html


<!-- 参考信息 -->