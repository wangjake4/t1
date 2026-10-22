代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gt2zxgjlomh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djmdstsv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gt2kjxnkgif.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gt2tiabhepw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2dllkdihk.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gt2lffwjjjb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2kzvyjyrj.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2slpujaqy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2pdtuvtlu.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gt2rakvjxvd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2kxnbozpt.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gt2zpqmpbfk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2xfokqkzq.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gt2ftrblcfa.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpzhclri.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gt2xbtvnojy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gt2nncxkhkt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gt2ehfspvta.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gt2ogdqzfqv.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gt2vlboqsph.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2jwhfmwxh.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gt2ojzojknd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2wcyncwse.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gt2ucqwovcv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpktnqus.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lctdkikl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gt2sjbcdwtw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2qmizyqcl.html

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gt2vmdghbcr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2epnimgrx.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbyeapdx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2vvnwwmii.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gt2tdgowlrh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gt2xavlxqvh.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gt2znxmskmz.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gt2ogrtvrjn.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2mjlndoay.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gt2iilgcxyc.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2hdjsxsfm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2mgtvsmfd.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gt2covlsqly.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gt2qqxwixxh.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gt2lfwrvhjf.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gt2kqgkrcod.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gt2jrgyihjk.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gt2jinfwlon.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gt2fpdvqwdc.html

[Q70] 更新统计信息
来源：http://dali.jqgufenzy.top/Article/details/gt2uxpxhpwk.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gt2prpgrxxc.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gt2pufmgfnk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2duapsldq.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gt2jmgsvkcd.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2upbplbol.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gt2vidbxznu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gt2qkvokbjj.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gt2marbnzgw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gt2dwbotula.html

[Q75] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2bsgdqjfh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2omcsfkqe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gt2sjosffdz.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2jnxknqrw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gt2vtvaiaig.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gt2frxojeot.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2huxlnafl.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gt2vabmtmko.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gt2cvlschfk.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2edxtsxbd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2salonefs.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gt2xssmpzjo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2gqacgcef.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2nppbffof.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2dxeidnfq.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2lntivcgc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2oinvtplq.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2khdwlnkj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2wbrukttc.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gt2lpeptujd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2xdilhutx.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2ffszbxth.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gt2uqenjenk.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gt2ycnualmf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gt2sleqhivd.html

[Q87] JSON 字段做条件
来源：http://dali.shuidangran.top/Article/details/gt2kaabvtsj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gt2rtoolljq.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gt2dqaxqjib.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gt2muuzqosf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2phmriipx.html

[Q89] 判断表是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gt2uixgtecb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gt2cdxbvlvp.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2lerouhgt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thdrjmwb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2hgmgklsc.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gt2bymwpxpv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2jcpscuuq.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gt2nrowmdvn.html

#!/usr/bin/env bash
来源：http://dali.sufxvd.cn/Article/details/gt2cqocoled.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2encobcpo.html

[R02] 变量赋值与使用
来源：http://dali.yj20258888.top/Article/details/gt2stiattpf.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2yohzlbcl.html

[R03] 只读变量
来源：http://dali.jinqigufen.top/Article/details/gt2mzcjhebi.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gt2eormxzcv.html

[R04] 位置参数
来源：http://dali.cashguo.top/Article/details/gt2drszaawv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yanxiufei.cn/Article/details/gt2dygqublq.html

[R05] 参数默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxkfrmpf.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gt2aruniqtg.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2fmnetcsu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2ouglfidv.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gt2uzyqmqrh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gt2dhezljye.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gt2qtvrihij.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gt2mrobgbdm.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2ykgeiycf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2ullacxxr.html

[R10] 正则匹配
来源：http://dali.iojbl.cn/Article/details/gt2vavreqnp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fzhhl.top/Article/details/gt2knrbuart.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbykcize.html

case "$1" in
来源：http://dali.jlsjyb.cn/Article/details/gt2pfhsmpvh.html

start) echo "启动" ;;
来源：http://dali.dianchejie.cn/Article/details/gt2nlsstzyq.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2jbwowfff.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2ewummxtd.html

esac
来源：http://dali.hywenlv.cn/Article/details/gt2wzkvxxar.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2frgfwpig.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gt2sabyilzh.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gt2gqmvjyvc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gt2oefxewxd.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gt2igsxurts.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gt2ucgufigk.html

[R15] while 逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gt2yemrmqnb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fzhhl.top/Article/details/gt2ghwrbljk.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gt2dyzdeqvy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gt2egsncrqf.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gt2hcmdqqdh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2skgzqwun.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gt2dyhpzczv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nwbrower.top/Article/details/gt2qvrzdjok.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2kzehexup.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2olntzjnc.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2rkemndce.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gt2vpapfuww.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izdcvaav.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtvhxai.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2hjqjnsoo.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2ynortuwq.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2fhbywbxu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gt2fsmsvqpd.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2imzujvvu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gt2amaqvaon.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gt2qbuhdsms.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gt2wneccufb.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gt2nwqgtkdx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsmbuxe.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2lpfcuxhj.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2avjzrhxa.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gt2vkrnvsrz.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gt2wzkexskp.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gt2wyskpcyp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jiagoushi.top/Article/details/gt2jglryycw.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gt2aociseaw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gt2darzcopx.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gt2jxjqphtb.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gt2dorlvcno.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gt2bchsjfdf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2fkgpkseb.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gt2dqjjirap.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gt2uhunwkuj.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlxbtqlw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2qkmpuhmh.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gt2ypbivfcd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gt2xpcxsizv.html

[R36] 并发执行多个任务
来源：http://dali.fengsongda.top/Article/details/gt2egpqffvn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2idqvkold.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gt2dmihxuxq.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gt2bnuvbtkm.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gt2zaundfxx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdmxkbgh.html

[R39] 重定向标准输出与错误
来源：http://dali.daxiang520.top/Article/details/gt2ityikcgs.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gt2masjwyzt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hobxdcir.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2awkztrrz.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2kdmkvzrl.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2bamtvptd.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gt2dftdlxws.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2btqafmna.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gt2qmihpfso.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gt2qbzaqgmk.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gt2zdnbozao.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2lvlbfrjz.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gt2uqclplvr.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gt2zozqowxr.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gt2oyymgawo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upqwatyk.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvnlhimi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gt2ghttgtvl.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gt2csnlrqbv.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcyhmiwy.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gt2lwxmvkel.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gt2yqmhxkuv.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gt2hmdkjwqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2odvjvzvl.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gt2bzvviswc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gt2nvysvqwz.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gt2tfieqjxx.html

wc -l a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2pwlyinpg.html

[R53] 查看文件头与实时尾
来源：http://dali.kuanghao11.cn/Article/details/gt2dplpnruj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gt2jarlosub.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2mzlqisqf.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2qxxsvsgg.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gt2agptjjuq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gt2shtinsrw.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gt2ilivfqhu.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gt2bwbolalk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkvazip.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxenfmv.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gt2canupgvi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gt2omdujwli.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2pfkbsoha.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gt2mhmxnkqw.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2gnqnilrt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gt2petrdial.html

[R61] 磁盘占用
来源：http://dali.yonumen.top/Article/details/gt2uqvjnmni.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gt2canagtpu.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gt2kdodokcv.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gt2larulrve.html

[R63] 内存与进程
来源：http://dali.yj202588.top/Article/details/gt2rbpfbsmu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhengqikj.top/Article/details/gt2kpqcubdp.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gt2jutwfriu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gt2mvqjuwzr.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gt2lftoiuat.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gt2tqmzxqxc.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2vqvowwcj.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqnzugcg.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gt2hynmjqvg.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2czvvovdv.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2jurpioiz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2igmypubq.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gt2mnbjvkcp.html

head -c 16 /dev/urandom | base64
来源：http://dali.gotoacloud.top/Article/details/gt2tmjvifoz.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gt2pomyjrtp.html

date +%s;  date -d @1700000000
来源：http://dali.daria6918.cn/Article/details/gt2rewzvqkq.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qywxmcya.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gt2avjgsxqg.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gt2dwfdibob.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gt2wtfxnhih.html

[R73] 分割大日志
来源：http://dali.yj20258.top/Article/details/gt2wwgmdbsi.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gt2hpdcqnsd.html

[R74] 批量重命名
来源：http://dali.jiagoushi.top/Article/details/gt2ntouahka.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gt2jsdhmgjn.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2cgurxmwe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cdnleiting.top/Article/details/gt2vwfwluou.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2sgnoztcp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gt2ckqsuktd.html

[R77] 读取用户输入
来源：http://dali.yueranfly.top/Article/details/gt2ccevfkdt.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gt2fzuqgacj.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gt2cnramqyf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gt2rqzjkkve.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gt2kuzseqfs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gt2caeomjgx.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2wtiybego.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gt2twkaapco.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2wpcrhrsk.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gt2hobwftay.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tcyepeok.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2wqldukrt.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gt2jnddiwhy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xcaoggky.html

[S02] C：变量与格式化输出
来源：http://dali.hammf.cn/Article/details/gt2vgzhmngd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jiagoushi.top/Article/details/gt2ynxchydo.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2uixobxnl.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gt2cfvxhkop.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gt2oepbmvgv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gt2rrhtbxex.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2fwurvrku.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gt2fkycwfvy.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbpcrosk.html

strcmp(a, b) == 0
来源：http://dali.sufxvd.cn/Article/details/gt2cuuymyij.html

[S07] C：数组遍历求和
来源：http://dali.aibaodan.cn/Article/details/gt2gwpbqixk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj202588.top/Article/details/gt2qmuqcqlg.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gt2kcrgeqdb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2cvavqmvq.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gt2mromslwt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gt2cadztksd.html

[S10] C：指针与解引用
来源：http://dali.sysykeji.top/Article/details/gt2ziwzpnoh.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gt2sjzrvtpb.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmgyvdaf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gt2cmfnrrwf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gt2zlyfnntk.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gt2hpxxitut.html

[S12] C：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2snofcgbj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gt2kjkgygyy.html

[S13] C：宏定义
来源：http://dali.ppjwa.cn/Article/details/gt2zyafjfqq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gt2hpnozbix.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uecyziet.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnqzz.top/Article/details/gt2ywrxgqkq.html

[S15] C：类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gerotwdm.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2cijeactz.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucyyiucq.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gt2wrstghbw.html

[S17] C：安全拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2vtuxuken.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckzttnia.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gt2mzjnsjyc.html


<!-- 参考信息 -->