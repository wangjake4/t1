代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gt2blhnvhvu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gt2yygpxliy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gbzbewgn.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gt2wramhwzn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gt2pfzatvhe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbrrlkub.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gt2bamaixrw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sweek.top/Article/details/gt2rjvjzmzk.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2ilswadnq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qftcvmnh.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2snqspbsy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2trhyvkdl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gt2feimbvsx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2ifspqqzm.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gt2nmoxxbwh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gt2sdorlsrc.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2zfwwuaxw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gt2vlrqtxhz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2eyztvwgc.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gt2apijgfdn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2zddjwlqr.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2pzckbypi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gt2todiodib.html

[Q51] 用子查询更新
来源：http://dali.bjfxy.top/Article/details/gt2vjzesdmu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yfqcahji.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gt2aqxeunds.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2dslcnvnq.html

[Q53] 按条件删除
来源：http://dali.chenzaomai.com/Article/details/gt2oivebqkl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gt2zqoabkqd.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gt2caxmgohs.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gt2wdhqaxlw.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gt2kcchqyxi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gt2cuewincc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqeetzlf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2bgyleaxd.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gt2gdbuopmk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkfywcbb.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2ellkqtrm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2kteubjgb.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gt2jhkgosrr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2fpghkvmg.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gt2xqrakwxm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gt2qzjivjkz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2biffphrf.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gt2dkybdcuv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2iixlqfxj.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gt2mzrmkjgf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2ojibheey.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2xbvsruxk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gt2fsczekym.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gt2iyyhoxkm.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxtvabnx.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptvxbtwj.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpnotzis.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gt2nqfgmqqg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gt2nefjsqrk.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gt2uvjipjek.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gt2gwusephu.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doqdobcf.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2eoispzwo.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2nsmkquuy.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gt2zzxxxxyc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onnekdnm.html

[Q70] 更新统计信息
来源：http://dali.yanxiufei.cn/Article/details/gt2wjifsuoz.html

ANALYZE TABLE users;
来源：http://dali.jlsjyb.cn/Article/details/gt2seukcrmk.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gt2vkwxhlxl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gt2jnoeutnx.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gt2jicyftkt.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvikkngs.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gt2ybzagfbl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hfpthk.cn/Article/details/gt2gwldlkfq.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gt2pwlialbr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymmmfesq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqclexm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2brfwtnid.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gt2agpbofoj.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqmofytp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gt2kgsjbcsa.html

[Q77] 时间加减
来源：http://dali.sxryk.cn/Article/details/gt2pwhrdaft.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2jarevljd.html

[Q78] 当前时间
来源：http://dali.chenzaomai.com/Article/details/gt2wwtkkvvp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gt2oowkoycn.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gt2rtuvalzs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzwvdifm.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gt2tjvodxss.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2uadpsjal.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2lsseobca.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2ubeiojuj.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gt2sretiioh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2arbigxjg.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2zuzqjetn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ieudyhal.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gt2kpjhynni.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2wwhrhwnz.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gt2jywqekjr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ivvv.top/Article/details/gt2acpziovp.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2cixiltgb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gt2vlppmmnm.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gt2vhnkjfee.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gt2erhfsxlh.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2jafwaycq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gt2rhonqcnb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynvugkyn.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2kvrehrtz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangdashe.top/Article/details/gt2gdpllqir.html

[Q90] 生成序号列
来源：http://dali.zycfv.cn/Article/details/gt2kpgvrzpi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gt2nrlgxhfy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2twglhgjt.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gt2cxshzymp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2iabtbuku.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2hkxddtoo.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2gxvwydbk.html

set -euo pipefail
来源：http://dali.aizwys.cn/Article/details/gt2hxcnzxzb.html

[R02] 变量赋值与使用
来源：http://dali.yangfankeji.com/Article/details/gt2bbswtywx.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gt2hebdlfev.html

[R03] 只读变量
来源：http://dali.nanxinkj.top/Article/details/gt2vdbdrklr.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gt2jvoydauq.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gt2sllralwa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gt2lhsmtivl.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gt2kqqpeevu.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjdlxvjd.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gt2zjjjkijh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2grojxbye.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2akiwocjz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2pqskboqa.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2jzrfmxde.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2xoxrswll.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2bmhelaux.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gt2hvhrxtwj.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rtdvzcre.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gt2nrzhvedu.html

[R11] case 多分支
来源：http://dali.xinyue.icu/Article/details/gt2uqwskzjv.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gt2jrmkgzgj.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gt2lskbywcu.html

stop)  echo "停止" ;;
来源：http://dali.ppjwa.cn/Article/details/gt2gzfdytfy.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuvbqvvt.html

esac
来源：http://dali.jinqigfzy.top/Article/details/gt2ramekfmz.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2gponejnb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gt2zisgvobh.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2stfoyumm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2yuwkpcje.html

[R14] C 风格 for
来源：http://dali.yongpay.top/Article/details/gt2mjmvyxse.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gt2jqlylord.html

[R15] while 逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2uigghbti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2xxziqkxf.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgszldnq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gt2wuktylpa.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gt2ppwlgxan.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgkqxet.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2zshqbcuz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2yequwurj.html

[R19] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2zusorduv.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gt2vcgpsxre.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gt2zbnmmere.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2fumytsus.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2uyviohkb.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gt2bqquycni.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2arovqmql.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gt2yxhicjrb.html

[R23] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2zswuhziz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jiagoushi.top/Article/details/gt2goinuruh.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2ywrsrmhm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dianchejie.cn/Article/details/gt2aldeccko.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gt2sbpwinnf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2aahgbiat.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gt2synpozsa.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfvuvpx.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gt2qqhhlgep.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gt2eaeehmmq.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gt2lxmgwmex.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gt2mscuathr.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2yzygiupk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gt2quhnrzfx.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2bmdysnhc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gt2phqpzozk.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2xppmoaba.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2dsvuipoe.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gt2psfvieha.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wyvciaup.html

[R33] 捕获错误并提示行号
来源：http://dali.chenzaomai.com/Article/details/gt2yjiojvlq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.mhx1999.top/Article/details/gt2wcnxphfe.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gt2htdjqfhu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gt2wrjrxckr.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gt2ehhtxpzm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gt2lohqutmq.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gt2bydicxch.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2fereawqe.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2jmvhaqzi.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gt2cigyojtn.html

[R38] 管道串联
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzfkavpt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gt2vmywhwca.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjphlowd.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2uuhrczhp.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gt2spncwavq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdlzfzd.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gt2ptrpypgh.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2tasyzadr.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mcjdghgd.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2lugatlwd.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gt2duvtlnmy.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gt2pphzfohb.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gt2ztvlanit.html

find . -mtime -7 -type f
来源：http://dali.yj20258.top/Article/details/gt2rfvkzkbh.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gt2jpvqtamn.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gt2geagtgwm.html

[R46] 递归替换文件内容
来源：http://dali.svipenyu.cn/Article/details/gt2fainttww.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cheryme.top/Article/details/gt2pgxlxlrv.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gt2tmyjgdub.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2vdcisfpn.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gt2caolbfkb.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gt2xysgpeqx.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gt2lrfylytp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gt2bfmoblso.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gt2yzbrruav.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2iastysit.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gt2lompwhcs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gt2naqbfizq.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gt2hoavfffu.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynrxzgof.html

[R53] 查看文件头与实时尾
来源：http://dali.havefunace.top/Article/details/gt2jhjiawjl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jlsjyb.cn/Article/details/gt2xtmhffjf.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gt2mvzuojxn.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gt2jemxsxii.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gt2wwqpjgnq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gt2hufceucg.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pcsdivxg.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2ggmhxsgj.html

[R57] 远程执行命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdpzoswj.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gt2urxqbhll.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gt2uqrdytsl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gt2hmaupsnf.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gt2usapzbyu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gt2nmqscnti.html

[R60] 只看 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2mqupfdku.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuetiantiany.cn/Article/details/gt2qffzbsme.html

[R61] 磁盘占用
来源：http://dali.cqqwz.cn/Article/details/gt2dobrgykr.html

df -h;  du -sh *
来源：http://dali.sufxvd.cn/Article/details/gt2skfwqrvu.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gt2sqtvnsyf.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gt2uiufxpcz.html

[R63] 内存与进程
来源：http://dali.jlsjyb.cn/Article/details/gt2vohyuknc.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gt2ouzuuwwl.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gt2wiejozaz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gt2lguhplgy.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gt2lzymxkss.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gt2oqysglao.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gt2zswvzxnd.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gt2scjbuohu.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2uevyyukl.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gt2tjmplfhi.html

[R68] 计算文件校验值
来源：http://dali.hongshengwenyu.top/Article/details/gt2sachyhgm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2mzrsttxj.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gt2yybfrbfh.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gt2kankstty.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gt2qjrlywbc.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gt2ghylaana.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gt2lnfmqbfh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gt2rcotkbyg.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gt2rzowdjan.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2jkmysxkb.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gt2wilhsfgx.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gt2afdjgzmq.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2gagtuimr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gt2vgslcdim.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2acdzlmnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2qnihjqpq.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gt2oddrhmwe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gt2gyxxqvfu.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2obhwpuoo.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2jbuprsgq.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gt2bqytptoo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gt2zjxzfgcv.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gt2bpnyaajb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhengqikj.top/Article/details/gt2kbtligdr.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gt2pycdwsdv.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2qnxorqpa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2lxsroikz.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2zdvklodp.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pviegbyh.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2zjobgfzu.html

#include <stdio.h>
来源：http://dali.xziqi.cn/Article/details/gt2nfgtifei.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gt2qqobmput.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2wmcrpdbg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gt2cwgwzfob.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2dznftazn.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gt2tjdtyrnj.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcavjzrk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gt2wcoajnek.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2hezyyrod.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gt2rpdlirlb.html

[S06] C：字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2lpsjxdgj.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2hluivnyr.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2ystdtmld.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gt2hykiaggq.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gt2mglicdbz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gt2yxrfsdpd.html

[S09] C：结构体定义与初始化
来源：http://dali.shzxlz.cn/Article/details/gt2xzguqaqx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ffcxxhkq.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gt2xdjjwoza.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gt2ivrexgqt.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qisfdqyp.html


<!-- 参考信息 -->