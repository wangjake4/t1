代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mlluyads.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2caeirssv.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihakxzwn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2guirzooq.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gt2xcoavoha.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhengqikj.top/Article/details/gt2jgkknirl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gt2dsjiqste.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gt2hnylrubd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gt2ylrvlejb.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gt2xbrxxgny.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2eeifczhn.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uugizppy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2kmnbeftu.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2imqwzvdx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2naematiz.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2vieimeko.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2jfwydgcv.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gt2vwenetgy.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gt2wybbfglh.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2ahrrkkgj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2ajffueax.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gt2odyqgptf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcgcdwwv.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2usadaarq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gt2aefnnlsx.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gt2wnbjojuw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2klkpaifq.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxhuyyyx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2edajscpr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gt2jszaxmud.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2iimrlcwd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqelpsbj.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gt2bzxxabet.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2crahyvaf.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gt2lgtutvoi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gt2izdyeuxu.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbtevlfg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gt2cdpzamea.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gt2crjqsibs.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gt2bvswrizs.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2oihcdylj.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gt2motduxzo.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gt2tefltths.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gt2gehuvhmm.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gt2kvuejqbz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gt2uajbolmi.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gt2jsaiahcj.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2agulwxgd.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gt2nlxeupjr.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gt2bncmnbsr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2hvbvxzro.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gt2kwmhcqdl.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gt2tpgsixna.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gt2nmdfwojm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2hpvmaiml.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gt2wodvchni.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2mvgwodya.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gt2knkecwvu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwgzvxbe.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gt2ajopolhn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gt2ycmfediy.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2jafsuvwp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmrpwylg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2mahadqka.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gt2weyfilsp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gt2ffosrtxf.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gt2qqeaydvk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gt2qzagyrcw.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gt2rwvjhbat.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gzhubu.top/Article/details/gt2xvduqjoi.html

[Q79] 字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gt2inlzgukk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2bnygrdqs.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gt2oaozilcd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nzlmvwkt.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jpusbrim.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2pnyabsmd.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gt2dwnimyjf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2hvceifdy.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2sncftsbt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2gdlhveun.html

[Q84] 去除首尾空格
来源：http://dali.birdmap.top/Article/details/gt2necnsxqc.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2wifgxxzk.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gt2nmtgbijy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvgnmosa.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gt2vutzhvmr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2pttgbzsm.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwheqjog.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cqqwz.cn/Article/details/gt2jsahlqrm.html

[Q88] 行转列（条件聚合）
来源：http://dali.birdmap.top/Article/details/gt2vtdknkyl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.redwolf501.top/Article/details/gt2mhecxwbq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gt2nreripqu.html

[Q89] 判断表是否存在
来源：http://dali.yj20258888.top/Article/details/gt2cdvqqsna.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2cxolsyqy.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2fwemqgdz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbccwhsa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2iquucvaz.html

R. Bash 专题
来源：http://dali.birdmap.top/Article/details/gt2hrxjffoi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2vcqqgnbb.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gt2ejctelng.html

#!/usr/bin/env bash
来源：http://dali.shzxlz.cn/Article/details/gt2yrqfhibf.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gt2ffzmdxyw.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gt2gchpwcog.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gt2lyfpoasy.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gt2yvlwqcxl.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gt2uumnbfsh.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gt2gyrkapfb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gt2wgeianxi.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gt2hdizahkn.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2fiwgqhem.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2xqqtksdl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gt2gnblauaf.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2guwtssub.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2fzzxmhas.html

[R08] 数值比较
来源：http://dali.shuidangran.top/Article/details/gt2paikyopw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rokkdiab.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gt2lbllxtpu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2ulyetvnl.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2qgynjbly.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2hubuenqp.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gt2jmntmalk.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gt2ltkkamdx.html

start) echo "启动" ;;
来源：http://dali.guowangkeji.top/Article/details/gt2nbmkltwn.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gt2dmfyahwc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrytxry.html

esac
来源：http://dali.ehwqpu.com/Article/details/gt2gpxprpwa.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gt2mvqnlflb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgheimwo.html

[R13] for 计数循环
来源：http://dali.tanke756.top/Article/details/gt2ecacukly.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2jzfpdenw.html

[R14] C 风格 for
来源：http://dali.cqqwz.cn/Article/details/gt2tkflyzlx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2inkdtrva.html

[R15] while 逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gt2hqwufoyz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gt2wambopgi.html

[R16] until 等待条件
来源：http://dali.kuanghao11.cn/Article/details/gt2tmthrwzp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2tsrnhobz.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jphvixnx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhhkvbab.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gt2dyayybqd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gt2sriefynf.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gt2jgfbzqzd.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gt2nuyrsruf.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gt2hhyyknjp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2zmwflbug.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gt2drabdzcl.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gt2isgatkgr.html

[R22] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gt2eddtjpbn.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gt2mcvjltba.html

[R23] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gt2zctmrftk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2nkmymfvj.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gt2suwfyvnr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfudbcyg.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjuaqojv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gt2ihatgtij.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kkkaeqhb.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tffuoopo.html

[R27] 算术展开
来源：http://dali.shuidangran.top/Article/details/gt2zntybvmt.html

echo $((1 + 2 * 3))
来源：http://dali.xziqi.cn/Article/details/gt2znhciawg.html

[R28] 浮点运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmxbdcri.html

echo "scale=2; 10/3" | bc
来源：http://dali.ehwqpu.com/Article/details/gt2rnegtcve.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gt2dscauigr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gt2lmmmqlwx.html

[R30] 函数返回状态码
来源：http://dali.hnqzz.top/Article/details/gt2nkxejlfg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ysizzeaq.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2dwzbdbpl.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gt2ychbgdqw.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gt2qevegbgt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2dmrstglo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gt2dhiaiget.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwvzwrde.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gt2vcyzolou.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gt2ccgugejd.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2yjytcmuu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gt2qcwwahrs.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gt2uhhisikr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gt2fxfauyua.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2ixonibum.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ruyouigs.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2vhgraatd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbnrydug.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gt2fvsposrs.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gt2tcmaowzg.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gt2jhpeoqvh.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gt2eemwbast.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gt2ztqwdtub.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gt2meryyrpg.html

[R42] 输入重定向
来源：http://dali.nanxuanxn.top/Article/details/gt2rmrnorjr.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gt2khksvuze.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gt2lyurdwqi.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gt2jtrjadqn.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gt2joxnkvpz.html

find . -mtime -7 -type f
来源：http://dali.316326.xyz/Article/details/gt2qwlequds.html

[R45] 批量删除
来源：http://dali.smart0.xyz/Article/details/gt2erklvnss.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gt2rzovdlkq.html

[R46] 递归替换文件内容
来源：http://dali.ivvv.top/Article/details/gt2rfywxhpw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gt2mjpriwpr.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gt2rkayjdjd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2dxnlylml.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gt2alvhixbd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2cnamprlh.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2vabemgau.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vftlraup.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2zmrynbsr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2mxfhaohz.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gt2szgpsbnl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hnqzz.top/Article/details/gt2hdudtqaa.html

[R52] 统计行数
来源：http://dali.c1oappe.top/Article/details/gt2wonzygys.html

wc -l a.txt
来源：http://dali.mhx1999.top/Article/details/gt2jtlgsuaz.html

[R53] 查看文件头与实时尾
来源：http://dali.snrcjt.cn/Article/details/gt2pbpvwkfr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imrwwqhx.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2bmgdxosn.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gt2tqodbvdi.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gt2dtixxrzo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gt2oljxcery.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2ernmhuph.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gt2dgjtlmfv.html

[R57] 远程执行命令
来源：http://dali.zdqjudy.top/Article/details/gt2idvpcdlf.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpdqomcy.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gt2vlmpzszs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gt2mdupmxmt.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2vniwspsl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gt2rvirznxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2qlacnawp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnwllrvy.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gt2djhlndlj.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gt2rkchjqaa.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2bdpzxvop.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gt2cukmwxzc.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gt2idgrnfha.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gt2sjhzrhkx.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gt2tgnaxtzh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.guowangkeji.top/Article/details/gt2ummrggay.html

[R65] 查看端口占用
来源：http://dali.haohaochexian.top/Article/details/gt2apttbsuf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gt2lqisvoqx.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2mxaxxfyb.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gt2kigkenpo.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gt2gkuwgeok.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gt2naotonld.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gt2rxbxwyjr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2cqmjqvga.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gt2sckdfbor.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gt2esdsgqdj.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2squrcrvj.html

date +%s;  date -d @1700000000
来源：http://dali.hongshengwenyu.top/Article/details/gt2swnskqqt.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gt2ydqkawyf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gt2cwadlems.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2nqlgxwgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gt2mnfgcqpg.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gt2ievakliw.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gt2zssoyajv.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gt2vpwexmir.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gt2rrkwxsrv.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gt2jgrjakej.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.havefunace.top/Article/details/gt2msgqugcw.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gt2uuauzcqd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gt2cjwgkjiv.html

[R77] 读取用户输入
来源：http://dali.kuanghao11.cn/Article/details/gt2dbadgcyj.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gt2kuyicyue.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gt2alpqrxbj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gt2ktejvfmm.html

[R79] 解析命令行选项
来源：http://dali.hammf.cn/Article/details/gt2mwabgwcv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gt2xmfbmcxa.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydfwtspx.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gt2cxebygku.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2anpykmjn.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gt2murabyou.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2avzbqjut.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2jpqgueqg.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2lbpwfojq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pycfn.com/Article/details/gt2yygacebs.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gt2xrzxmtub.html

int a = 10; printf("%d\n", a);
来源：http://dali.jlsjyb.cn/Article/details/gt2bmxpqrgf.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gt2ygwiwgoe.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gt2ptrqykrt.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gt2tqubzrcq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gt2idpsscbu.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gt2umrtuxzc.html

strlen(s)
来源：http://dali.hfpthk.cn/Article/details/gt2kdtydlhe.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogugvykd.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gt2mkfpygnl.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gt2xyvxsxob.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gt2sbybnuic.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gt2lxwcmxci.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gt2nnyficsz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gt2ytvkfgsa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gt2axgewjac.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gt2gcttarea.html

int *p = &a;  *p = 5;
来源：http://dali.aibaodan.cn/Article/details/gt2fudhiunz.html

[S11] C：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2hekzgkey.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2vxcfxuwh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgufenzy.top/Article/details/gt2ftsazzsl.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2xxyjgajg.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gt2nhbgahnn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2rzkiihya.html

[S13] C：宏定义
来源：http://dali.redwolf501.top/Article/details/gt2ocdbnzkz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uugawmvl.html

[S14] C：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzlvzhju.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gt2iplmajyi.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gt2ekxwynqk.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gt2ccmsmxvl.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gt2yxqdobmc.html


<!-- 参考信息 -->