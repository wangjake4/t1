代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gt2bugdogai.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gt2fqmmsqze.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gt2tbesjyrz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2yeypvxqf.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gt2hepgitil.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gt2fsgvchrn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gt2okhbvlcw.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gt2qykkyyyj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qcqjrgmy.html

[Q50] 批量更新
来源：http://dali.vqdsnc.cn/Article/details/gt2fhfmufmj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sukpyoim.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gt2slvcnozo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2nmmpcebx.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2oychocjr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwiqyqtt.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkeltxaf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gt2jbmfoaow.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gt2lcbkhyvv.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gt2ymbqqotb.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gt2uxektfim.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2kzusikgf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gt2jqxqpxun.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gt2ocsbrejd.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gt2erubmrxd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2mlsaghrf.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gt2klcfsdzy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2summzjdw.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gt2gaphzgyz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gt2idhjrvqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gt2ykuwwyqq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gt2ftnygneh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2kgdtijoo.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2ychzoanz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2htasasnx.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2dcqvfnnb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2elfvkfpj.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gt2eseffntk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gt2tfcbvlhw.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2acpawroj.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gt2kmklfldc.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gt2avbcjhxv.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gt2gxamgrry.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2zaroeqmf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntzbfsie.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gt2jnezviww.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gt2uqbeumid.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2mapdzsaa.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2jtckdcyz.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcrercwf.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gt2wkrqeiqy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gt2lidcnctp.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gt2dieylbyr.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gt2whjcmfdg.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahzhuzxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gt2oykrlzkx.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2gsulfaih.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2hlkxrywk.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gt2hpstxgvr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2okhtedsc.html

[Q74] 强制使用索引
来源：http://dali.9152youxi.cn/Article/details/gt2irhnqzmu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2smktsqap.html

[Q75] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dygikfta.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2gddsokbt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2qburkvfy.html

[Q76] 按天统计
来源：http://dali.jqgufenzy.top/Article/details/gt2ofhwkvan.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dianchejie.cn/Article/details/gt2nhgqvwjx.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gt2mdjixlqq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnxiangtu.top/Article/details/gt2uvttnaav.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gt2zkjwbrmo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2pjmzajzj.html

[Q79] 字符串拼接
来源：http://dali.sweek.top/Article/details/gt2cumgdpuc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gt2zhdhryyy.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2wyxkwqqy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2douxhjhh.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gt2chmhfqlk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2dewyfuzp.html

[Q82] 字符长度与字节长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjaxnndz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2aacjhfrz.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2cbzesjsn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2yantjhiu.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gt2bqnvczpb.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2wgvbhdoi.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gt2jlupghei.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gt2ylrqwnog.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2avheyqas.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gt2kvfjosxe.html

[Q87] JSON 字段做条件
来源：http://dali.quarkkingdee.top/Article/details/gt2ufhkwdgh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppcbvvlq.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2bveavydu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gt2hlgbizhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2mxevqhxv.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gt2eppecmpg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2lldhphev.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gt2ccrlggjn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gt2iafvcczk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2umflouvb.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gt2awakxaki.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2yrpzrhvg.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gt2fsjakdaw.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gt2shklujpp.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqorzsim.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gt2gauilqps.html

name="Tom"; echo "$name"
来源：http://dali.yanxiufei.cn/Article/details/gt2gnzhvhil.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gt2zcekpehp.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gt2jmtwmant.html

[R04] 位置参数
来源：http://dali.zhixingplan.top/Article/details/gt2ywzmuitb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gt2ysnkdzlq.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2pvbwmdnz.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gt2jrxbwbdb.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2mzmvieue.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2mfjkyhlh.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gt2xifulqow.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2gkpakbfg.html

[R08] 数值比较
来源：http://dali.sysykeji.top/Article/details/gt2bouhktkd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gt2cbcwqxck.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2aiakcapt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gt2wqphahzb.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2uspwzisi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqqoxqzb.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tombhhnx.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gt2buymuyjp.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2szurpfwe.html

stop)  echo "停止" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pverbcyw.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gt2szwtaxup.html

esac
来源：http://dali.gotoacloud.top/Article/details/gt2zpjtaypt.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gt2digmfkex.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxdnyfgx.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2niqfbbqv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gt2qdjnyfrh.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2uzstifht.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gt2atezpwbr.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2esmyktwl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dianchejie.cn/Article/details/gt2zpimbzfg.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gt2yldgfqaw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gt2palzwlxx.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2iqiwbqop.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gt2kgocosip.html

[R18] 遍历数组
来源：http://dali.dashuyun.cn/Article/details/gt2psgmodsq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gt2rddyszvt.html

[R19] 数组长度
来源：http://dali.tanke756.top/Article/details/gt2rdjsfxet.html

echo "${#arr[@]}"
来源：http://dali.gzhubu.top/Article/details/gt2avnmzuol.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gt2ldmyvuld.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gt2ptapbaqa.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrlaqapd.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gt2vsnntkdu.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2epjrricp.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gt2pplodyrm.html

[R23] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2zqoxjxyl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gt2lvzrgghr.html

[R24] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gt2cblqiodm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2caslnsla.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfqrjsxi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gt2vwriupeb.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gt2mhhwwnkn.html

now=$(date +%F); echo "$now"
来源：http://dali.cashguo.top/Article/details/gt2wapfgpop.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2aeowtwck.html

echo $((1 + 2 * 3))
来源：http://dali.cheryme.top/Article/details/gt2nzidzmqs.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2bxwddusy.html

echo "scale=2; 10/3" | bc
来源：http://dali.dashuyun.cn/Article/details/gt2orrknbsb.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gt2eahugdul.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gt2kruqypiy.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2xugjnlle.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gt2ochcqijt.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2nyohacnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2rrqimmsg.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gt2zprabpwv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hysaishi.cn/Article/details/gt2zyldeqvd.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gt2hnudyvjp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kfaiykpr.html

[R34] 退出时清理
来源：http://dali.aizwys.cn/Article/details/gt2giomveuq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gt2rldmmmfn.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gt2efmxxpmn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pycfn.com/Article/details/gt2xtqwrnrn.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gt2azkgnpyw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2ymmizjmt.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gt2bxagojiv.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gt2okfbnepw.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gt2incvxavp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2esrmasba.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gt2tmzqgfwo.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2liqkpuqy.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gt2agigwbgb.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gt2gsutoysk.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gt2gefmznre.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gt2uvqorjva.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gt2diuyrluf.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gt2rohfcnyc.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gt2urvijulq.html

find . -name "*.log" -type f
来源：http://dali.gotoacloud.top/Article/details/gt2kaixednk.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gt2afsiegom.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gt2babsnspw.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gt2zydsdjwt.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gt2pyllemyt.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gt2xknrrzxl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gt2rtkobeob.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gt2qppwoqkz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2uxuiqjke.html

[R48] awk 取指定列
来源：http://dali.zhiwuduotai.top/Article/details/gt2arnqgtxu.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2vhartsvc.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2rycjpdsv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gt2sasggixd.html

[R50] awk 求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fipjgagw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2xdsyiuqd.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gt2qkblizxd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2oxklszma.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gt2bcrtwdbw.html

wc -l a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gt2igybjlsy.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gt2pyqeyxrd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gt2bksdrjax.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gt2wxminysv.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gt2eummgdtc.html

[R55] 压缩与解压
来源：http://dali.birdmap.top/Article/details/gt2nochchps.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gt2powtlncq.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gt2picvnkyq.html

scp file user@host:/path/
来源：http://dali.guannengcc.top/Article/details/gt2aecevcdh.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gt2fgxqveuj.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gt2lkmvyasa.html

[R58] 下载文件
来源：http://dali.fengsongda.top/Article/details/gt2vubncrdv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gt2ykylrgnv.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2poeqwwci.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gt2ccrvtpmz.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gt2kphhtpgu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gt2eohxyyng.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gt2xmefivhi.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gt2tmcjalcz.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gt2xvvmsjny.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2hydkpseo.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gt2cpopycsv.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gt2gqiwwqwv.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gt2awivnuig.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gt2zgewsysc.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gt2hgqiatfe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2bdzpbhjn.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gt2celxvnkt.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gqrxwlrj.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gt2ejeaxxls.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gt2xdknyecz.html

[R68] 计算文件校验值
来源：http://dali.birdmap.top/Article/details/gt2fsiiiokd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gt2gbwwshmd.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gt2ttfrdscw.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuxming.cn/Article/details/gt2mnfnfgmk.html

[R70] 时间戳与互转
来源：http://dali.jianghu66.top/Article/details/gt2ibefdlri.html

date +%s;  date -d @1700000000
来源：http://dali.iojbl.cn/Article/details/gt2qstbfscm.html

[R71] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gt2wagaxxcm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2possyefo.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gt2yujxsxph.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixzjddde.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gt2muknudzh.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gt2ftrqieul.html

[R74] 批量重命名
来源：http://dali.zhixingplan.top/Article/details/gt2lqcuukbg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gt2roumbpbx.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gt2pibfkcsj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gt2gscemeuq.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gt2krxlicfa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2cuncqttr.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gt2yscjnsys.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2liwtvsup.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xqlpvime.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gt2awpqhexn.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gt2lfbyoikt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gt2ttycdztw.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gt2ouufievk.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gt2yutgkxma.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvvhjgfw.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gt2dypfakce.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2tlrhkplk.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkamwfnv.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gt2fxgwcidx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmwoqscm.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gt2jtlytfwi.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2luouhnzs.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gt2fhmtemxn.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gt2wdglgalw.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gt2umvpiemm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2mcmiflac.html

[S05] C：字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwkhznyg.html

strlen(s)
来源：http://dali.yuxming.cn/Article/details/gt2duxnhacx.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2zvukvuep.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2tomossnn.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2uafkrhqt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gt2zyjkxcsp.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gt2dwewyjhf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aifeerct.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gt2tfdqsodr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gt2gbgodxpz.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2rryhlijk.html

int *p = &a;  *p = 5;
来源：http://dali.sweek.top/Article/details/gt2uyghxekp.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gt2hfxomtra.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gt2leyivjus.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xuanzx.com/Article/details/gt2equvjplb.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2hclfwpew.html

[S12] C：写文件
来源：http://dali.shuidangran.top/Article/details/gt2qxkqrcsf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2nytnjyoy.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gt2kdprpqwn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gt2gtwbtpdu.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2kkrhvcbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfctjzgs.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjruyrwy.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvupcggi.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gt2gnopurwm.html


<!-- 参考信息 -->