代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gt2grrqajpj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2vyrnigzp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gt2nhifxmqi.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtivbidg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gt2spbjmpdo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gt2wggbjyqg.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2icrnetnb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gt2bydmbkas.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gt2oirgfbbm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2bqoposnz.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2sxnoaced.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2tkfyojwk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2eevabwfd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2toxdsofm.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2cepvrbdy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2fbehakzp.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gt2coygtrkt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icsuxldw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gt2ciqdvvbl.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gt2regzkqmp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2wruvltba.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gt2jkziyiqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2nxfnbrky.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gt2krqvqtqe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuxming.cn/Article/details/gt2mxfxwdbi.html

[Q52] 删除指定行
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ssvbiwst.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2pbcfndxy.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gt2nmbuorce.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2ezntqfzh.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjjiijtc.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkxlvwvd.html

[Q55] 排名（并列占位）
来源：http://dali.ybcxt.top/Article/details/gt2mrjbwobw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwfyqgem.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2eurkufsq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wazmqtbo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qowdqcwb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2uofylbwu.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gt2lazejeut.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2raqwmhsz.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2iajxslav.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2rgvbxzvf.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gt2qlhfiagr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gt2kijcsdhq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2rysbyjfs.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gt2zifibslz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2cnlfgggt.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gt2uqmnxacy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2cpbmeqzz.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gt2dmyclgvt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2imerbqlf.html

[Q64] 提交事务
来源：http://dali.jlsjyb.cn/Article/details/gt2bjahzimj.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gt2vklupxhc.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gt2ywogsczv.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gt2washyhcc.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2bdrlaoth.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gt2darcsgza.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gt2ytvtyrhx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gt2edahvqbg.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gt2rhzqcwqb.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gt2unvkivsi.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gt2mnpjwfww.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2bfablcld.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gt2txrftqfx.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gt2wixgzgle.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gt2fltsbogz.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gt2itfdvsos.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gt2vzvnoddi.html

[Q72] 查看索引
来源：http://dali.dashuyun.cn/Article/details/gt2cpsnsqun.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2qizvsezn.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gt2rkhiupda.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gt2dqespcxl.html

[Q74] 强制使用索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stawxdwa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2vcnsioez.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gt2rwygvgdh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gt2osedkkah.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj202588.top/Article/details/gt2rzozkqkf.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2gctcvgej.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gt2bwgswuyd.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2nvfpsawc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gt2bhpfcwka.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2yqzcsqds.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2mqwfxcgs.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gt2wkdznbgz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skclwscf.html

[Q80] 字符串截取
来源：http://dali.hywenlv.cn/Article/details/gt2dddvebdi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ftcqtpms.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2dccsrpbb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gt2wnashilh.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgfzy.top/Article/details/gt2oukjehiw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gt2oneulaud.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gt2qovgoriv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2easrxtnf.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2ftwiezlo.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ahorqerz.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2bkyehgzc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gt2pwdbzhzs.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gt2xnukshzh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2arsvnrxe.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2xrdysxzu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gt2bhezcsql.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gt2asomptpy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2hvrrwijh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2oeyfxbtl.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gt2pwupsnqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gafgvlva.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gt2irpwwjrt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj202588.top/Article/details/gt2ekhhbear.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ndussoep.html

R. Bash 专题
来源：http://dali.havefunace.top/Article/details/gt2yepedlby.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zsafnhim.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gt2nbsunbda.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gt2npjiqldz.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucyodpsj.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2opxapzhb.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gt2ffkptllq.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gt2zolikkcc.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gt2jzrdvreo.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2hosbovxc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gt2yezbcfed.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gt2lcmpfhmn.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2yoztlldd.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2lboahtnd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2vumotqlm.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwgimfpd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2djlnykwy.html

[R08] 数值比较
来源：http://dali.yj202588.top/Article/details/gt2iaxzbeat.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjwywyr.html

[R09] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gt2nggvmrsr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2qfjdlvif.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2rixjfvhb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gt2xldkntnb.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gt2dzrcrgge.html

case "$1" in
来源：http://dali.hongshengwenyu.top/Article/details/gt2eykpmqgp.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2mslcwovo.html

stop)  echo "停止" ;;
来源：http://dali.yj20258888.top/Article/details/gt2dzluwnnv.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2rofbmmou.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gt2thdozxpc.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gt2dcpfvuim.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2qigjiswc.html

[R13] for 计数循环
来源：http://dali.yonumen.top/Article/details/gt2kqkwsgqd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2ipmxacrr.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2ogkluhtz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.guowangkeji.top/Article/details/gt2zjfiwxye.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2afffphdt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2yrswdwrw.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzyeqcrl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2jmiaqytz.html

[R17] 数组定义与取值
来源：http://dali.sxryk.cn/Article/details/gt2kheoijnz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yueranfly.top/Article/details/gt2kmeaqgrh.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gt2ywdphydn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gt2bxkzkypb.html

[R19] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2wnjeebsu.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2cthgvvdi.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gt2jmgqcrng.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2unauhizb.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cmfhdrcd.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqbvfben.html

[R22] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddoxnfio.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gt2pphlsbdf.html

[R23] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gt2qpjoflix.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gt2sbnnwlbl.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2zixcpohs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gt2dmxjvzga.html

[R25] 去后缀 / 去前缀
来源：http://dali.daxiang520.top/Article/details/gt2potzokdw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sxryk.cn/Article/details/gt2manuonev.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gt2qpcmturw.html

now=$(date +%F); echo "$now"
来源：http://dali.vqdsnc.cn/Article/details/gt2jrfmvqax.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gt2nzvlpomb.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gt2hgsfayrx.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gt2qgcrcxev.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gt2ggykpxwf.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gt2eojjlzmp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gt2inybtywo.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gt2ijkddohx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gt2tkgmoyrb.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gt2mvmabnce.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gt2eiqbtish.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gt2suwvotwd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2pcmbwdjl.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gt2iivrjqzc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gt2rvwapflt.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufbndfke.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2rzoyiokg.html

[R35] 后台执行并等待
来源：http://dali.gogol.net.cn/Article/details/gt2lpokuhra.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2vukhajbq.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gt2sxlictaf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ehwqpu.com/Article/details/gt2mqiytumc.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2isoillja.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gt2vurappsu.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gt2xqzrrifn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gt2sckoxjnb.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrnjogys.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2mcokmrgk.html

[R40] 追加写日志
来源：http://dali.fengsongda.top/Article/details/gt2zuhtkopb.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gt2nphvrkuf.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gt2ponmvflj.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gt2whznghpf.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gt2qbaovjyk.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gt2mymwizvo.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gt2ikjkiijo.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gt2lmgnmhdv.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gt2ofpacrhc.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gt2kjgtrazy.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gt2pwmatykk.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gt2bhnzajcm.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gt2frtbfgks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuanzx.com/Article/details/gt2bsyouynz.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gt2kejhexgu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cgjwsfkl.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gt2mngekepo.html

awk '{print $1, $3}' a.txt
来源：http://dali.sweek.top/Article/details/gt2gvjshpja.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gt2ulgpxwnv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.vqdsnc.cn/Article/details/gt2byqoabfp.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gt2oiqoirim.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2kybofzwv.html

[R51] 排序去重取前几
来源：http://dali.cashguo.top/Article/details/gt2pmnsbqcz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangdashe.top/Article/details/gt2cfjeoslk.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2wtvzactt.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2puyepbyf.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gt2wmscgcql.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gt2tbkdftwx.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gt2kmbeemxu.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gt2esxcrdgm.html

[R55] 压缩与解压
来源：http://dali.sufxvd.cn/Article/details/gt2uhafqxcn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gt2ihdteoxr.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gt2widjiubk.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gt2vvnicsvd.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2cbxejbij.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gt2unlhgvtz.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gt2yyafqojr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gt2vnsaiqky.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gt2ompailwd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gt2nemzdwha.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2cnbncpza.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2fyzysljz.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gt2pmsxhfck.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gt2pykdscnv.html

[R62] 找最占空间的文件
来源：http://dali.yj20258.top/Article/details/gt2dmpvdens.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gt2eoxkxqkc.html

[R63] 内存与进程
来源：http://dali.hysaishi.cn/Article/details/gt2ysfaaywn.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2iwnkwzgz.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gt2cbtmpcpx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xziqi.cn/Article/details/gt2jvgamujx.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gt2bsvwnaql.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gt2cvvedbog.html

[R66] 定时任务
来源：http://dali.dashuyun.cn/Article/details/gt2cyaarycg.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gt2jzxszyqt.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpxjvifp.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gt2qhnjsrbx.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2yhikvwhc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gt2jozqeflq.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gt2ihuvduzq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gt2anjxpgle.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gt2venicimt.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gt2dhzaezmy.html

[R71] 日期格式化
来源：http://dali.pycfn.com/Article/details/gt2jiacvwdh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gt2dxnrxfyr.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2wejvmojs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2ncgkkxyx.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gt2qwiavmsu.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gt2cmylhhxx.html

[R74] 批量重命名
来源：http://dali.c1oappe.top/Article/details/gt2nulnomwp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gt2gxvpolbc.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2xffajyti.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2lqyiioic.html

[R76] 使用临时文件
来源：http://dali.xinyue.icu/Article/details/gt2nuuhoklx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gt2atgwakhr.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gt2kcgahcmi.html

read -rp "请输入: " ans
来源：http://dali.jinqigufen.top/Article/details/gt2byblukol.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2tciyogqb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gt2mxkakazz.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gt2quivevmo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gt2trkeepde.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gt2bbvbtqwd.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gt2zlkclqgc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2urtiddlz.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gt2zsllsiqz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ebrjbrxs.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2xhoufwgy.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2kybpgced.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gt2aeaedctk.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gt2wovspfve.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2oqqvclac.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gt2lrujktym.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2aqdbkmcd.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gt2linxwrgq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gecuaslh.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gt2dgdbomib.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gt2mvesgxzs.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gt2yphoguxx.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzmbgimo.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2klopirrx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gt2hkmofghs.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gt2hyouqhco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gt2tfwnpthm.html

[S09] C：结构体定义与初始化
来源：http://dali.hammf.cn/Article/details/gt2qroffqrt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2rfhdswrv.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gt2zwzfxlwg.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gt2qqgorime.html

[S11] C：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2grqsmifg.html


<!-- 参考信息 -->