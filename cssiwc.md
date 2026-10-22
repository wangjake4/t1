代发 wailian999

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gt2xoectygh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gt2tkjprsin.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gt2aczwnudw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2lmcfiooy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgviyshz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gt2frrkgabs.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2wewzoaej.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nanxinkj.top/Article/details/gt2pxamogbt.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2klbmxppi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2rfwhzose.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gt2qwswdgvm.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxbjgsth.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gt2iraebfuu.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2ntgnlahe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkdelbs.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gt2bfvmrisp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2ikbnhxeg.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcsrvhif.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2orlqkhad.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gt2mvostubr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2uocyeqnd.html

[Q54] 清空表
来源：http://dali.zhongyouzk.top/Article/details/gt2kisdixmv.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gt2ciosdfuy.html

[Q55] 排名（并列占位）
来源：http://dali.yongpay.top/Article/details/gt2tmszwjnt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2cansjill.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gt2rywyjewa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2gflgmjtf.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gt2xfavkotq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2sbukyjkn.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gt2eyswevpr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgoghdsq.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gt2jarwclwa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2whiugvsx.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gt2wvwbxvxh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gt2lrfenbks.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2uvflgdfa.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gt2aopeywth.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2uqgtnlyl.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gt2eefhgxcd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2ggssnbuj.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gt2ymopbfeg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2xlfuuknv.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gt2pjvfihlb.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gt2ospxlxzl.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gt2pudguviw.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2nipgzums.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gt2lpngwjou.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gt2oclrvzbi.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gt2fuplzcay.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gt2xqfdjtxp.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gt2ljyirgms.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2rkrmtwqj.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2wjeotsbg.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gt2frvqypif.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gt2sdpgrygd.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gt2cnxucsqd.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gt2bifiybnn.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gt2cwejxbft.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gt2pqnlkufu.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2bvdsgdlt.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2wwjjucbr.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gt2ioecshen.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2jjcxkhsa.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2yqvfeeiu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gt2ucfpcrxx.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gt2gjpqvwoy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwfoudna.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2axtsersj.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gt2zmdoueno.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhengqikj.top/Article/details/gt2yxvqghlp.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2cdaxjnyn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gt2zfeyuflf.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gt2lhekbqnl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gt2junzhpaf.html

[Q79] 字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2cpaxnrey.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gt2eaoaedle.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gt2aommvxjz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2weoqbkrz.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gt2aehozcir.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gt2jyfagmuh.html

[Q82] 字符长度与字节长度
来源：http://dali.tanke756.top/Article/details/gt2bflodjee.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2iddakbob.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2wvifdxnd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2xsvkfajh.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gt2apuwkbvh.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2rwfskhdr.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gt2ahlawyuy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gt2ergzfsnd.html

[Q86] 读取 JSON 字段
来源：http://dali.chenlongwang.top/Article/details/gt2uynzfynr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gt2psmqxojs.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gt2zqerjkay.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.birdmap.top/Article/details/gt2ikilesot.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xewqtkul.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gt2ctygwhju.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2ixtnzvkv.html

[Q89] 判断表是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2hbujjwyw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2xwqexmth.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2fnnmhmdd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gt2ckibdlov.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ljvxanuy.html

R. Bash 专题
来源：http://dali.gzhubu.top/Article/details/gt2emovcgpb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2muzwpsbk.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gt2uhpskfev.html

#!/usr/bin/env bash
来源：http://dali.dianchejie.cn/Article/details/gt2kdacnvkc.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gt2wmhzrvwq.html

[R02] 变量赋值与使用
来源：http://dali.gaohongyu789.top/Article/details/gt2jkkbqsjr.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gt2cstazleu.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gt2lcfxbnyo.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gt2vxhqtqxa.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gt2iroydngw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gt2lbfrmvfs.html

[R05] 参数默认值
来源：http://dali.daxiang520.top/Article/details/gt2qytxaidr.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2utchcedj.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gt2dsfoknbw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gt2xsodzbmb.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2xjxlcubi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2kjovtogv.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqzvcqzl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gt2uaqeuecn.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gt2xpatkckf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2lpjpuxzr.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gt2jyiniglt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sxryk.cn/Article/details/gt2jufnviuq.html

[R11] case 多分支
来源：http://dali.ehwqpu.com/Article/details/gt2ruabxzos.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gt2jigpenrt.html

start) echo "启动" ;;
来源：http://dali.gzhubu.top/Article/details/gt2mcrdeqbw.html

stop)  echo "停止" ;;
来源：http://dali.cheryme.top/Article/details/gt2ssaiwede.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gt2ffnelsxw.html

esac
来源：http://dali.yangfankeji.com/Article/details/gt2merrfygs.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2jewryfen.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2oxabrkah.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gt2iiffhiif.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gt2xroerkwv.html

[R14] C 风格 for
来源：http://dali.yuxming.cn/Article/details/gt2yxqkqiyf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2lbhqssag.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cydtpush.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2pydyzyhf.html

[R16] until 等待条件
来源：http://dali.jiagoushi.top/Article/details/gt2jrmteqdb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2rvginfmn.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gt2hwxhdnux.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2muppnmqn.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gt2ulcaruih.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gt2fsfbdlyy.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2dotrxheo.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gt2zvzlzvrf.html

[R20] 关联数组（字典）
来源：http://dali.yvedp.cn/Article/details/gt2ztdjztbv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2immuahlv.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2seioyxkk.html

echo "${#s}"
来源：http://dali.shuidangran.top/Article/details/gt2tnwhlsnh.html

[R22] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qfzzdpfe.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcypjvmt.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlfywksp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gt2gjfplwyl.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2ooehlflx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gt2jfhmlpav.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gt2xjsklcac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yueranfly.top/Article/details/gt2vgduczqc.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gt2nnarvjtd.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gt2lderxmfa.html

[R27] 算术展开
来源：http://dali.jlsjyb.cn/Article/details/gt2zzfamihc.html

echo $((1 + 2 * 3))
来源：http://dali.hfpthk.cn/Article/details/gt2phxuoydw.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2jwruthnt.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gt2rhbfbuqo.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2grrogetl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luoahghx.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gt2hjlsrnkd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gt2zhpglfoa.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gt2ofkrlcwc.html

f() { local x=1; echo "$x"; }
来源：http://dali.haohaochexian.top/Article/details/gt2tlkrlvfj.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gt2bjyugrmi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2bijlsoku.html

[R33] 捕获错误并提示行号
来源：http://dali.hysaishi.cn/Article/details/gt2tcfxgwgn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gt2uadejviz.html

[R34] 退出时清理
来源：http://dali.redwolf501.top/Article/details/gt2hrnnzven.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltxktvpp.html

[R35] 后台执行并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wamuwsna.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gt2mtzuubsa.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gt2hdmakiwg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gt2mewbssls.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2nmksxuwg.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gt2fexorjip.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zemasmbl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2rhxmyoir.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gt2znsebkku.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gt2wiustabd.html

[R40] 追加写日志
来源：http://dali.yvedp.cn/Article/details/gt2ufmrwrvz.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gt2gnrgmpxz.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gt2wwhucakf.html

cmd >/dev/null 2>&1
来源：http://dali.ivvv.top/Article/details/gt2tkmsvzxw.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gt2owetjjkm.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gt2agrivsom.html

[R43] 按名字查找文件
来源：http://dali.jianghu66.top/Article/details/gt2cfnhdkek.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gt2vtslthwb.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gt2uisoitxw.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gt2lguodefp.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gt2cxnqyvuf.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gt2phyndsgt.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gt2qfrnsqap.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jqgufenzy.top/Article/details/gt2vgihrirp.html

[R47] sed 单行替换
来源：http://dali.birdmap.top/Article/details/gt2owuacgvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.svipenyu.cn/Article/details/gt2dqzgomyt.html

[R48] awk 取指定列
来源：http://dali.havefunace.top/Article/details/gt2lnegypoi.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2exiaqylf.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gt2oxltherz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gt2kdklieis.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2smeqyfxj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyvkeire.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gt2efntfxku.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ehwqpu.com/Article/details/gt2wumkzozq.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gt2mpqxlrwp.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gt2agopufmn.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gt2cazemdtx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gt2wulazipm.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gt2enymouiz.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gt2jyfdfzel.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gt2nosfhurj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gt2yjtvgbgp.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bemlailw.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2vlxznnzh.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gt2jiaqjegn.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2gpkiyelj.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgrtdvhf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fzhhl.top/Article/details/gt2byesjjbv.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iosdzvsy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.feifeiyinyue.top/Article/details/gt2yhscmnem.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gt2dkeulscr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gt2tlwyydtl.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gt2zvrhijwy.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gt2zqdktffr.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gt2liaflmau.html

du -ah . | sort -rh | head -10
来源：http://dali.fengsongda.top/Article/details/gt2lxvyngwa.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shibjtqy.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2mggfwuep.html

[R64] 结束进程
来源：http://dali.nanxinkj.top/Article/details/gt2waowhljz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.snrcjt.cn/Article/details/gt2dtbsglgb.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gt2uqfhfgmn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2czhlifev.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gt2hbabeuip.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztdaujlh.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2zrbqshzs.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gt2jiyyafrp.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gt2hyaibleh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2apmycehm.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjqbbxki.html

head -c 16 /dev/urandom | base64
来源：http://dali.316326.xyz/Article/details/gt2gqaynglt.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gt2tlyrjzmn.html

date +%s;  date -d @1700000000
来源：http://dali.wangshuangyany.cn/Article/details/gt2ympwavni.html

[R71] 日期格式化
来源：http://dali.cashguo.top/Article/details/gt2ddimhkgo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gt2konnmvjf.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gt2cmbgfqiw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gt2zubmvhat.html

[R73] 分割大日志
来源：http://dali.yj202588.top/Article/details/gt2ioopdevc.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gt2crbkeloq.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gt2xbjxiszs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzmtlcri.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2kimgheip.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gt2ghixwzdn.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isztqtpm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2kfstmxqe.html

[R77] 读取用户输入
来源：http://dali.zhongyouzk.top/Article/details/gt2cmaenpwy.html

read -rp "请输入: " ans
来源：http://dali.aizwys.cn/Article/details/gt2wzmwfxol.html

[R78] 交互式菜单
来源：http://dali.ydzc1.top/Article/details/gt2tyqkqhnn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gt2uvecthja.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gt2sqfwxlrm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmgcacwc.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gt2wlkvvxac.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gt2axgukzml.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2dojbjstu.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gt2nponjznd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzcjlnos.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2skuqarnb.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gt2lmpcjeoo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.mhx1999.top/Article/details/gt2rggvdnmr.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2waedcssx.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gt2amcggewe.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gt2ndojrxaf.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2tvkixzlz.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2newpjyoc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaalhwak.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2hkwunesj.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gt2zijjvqsk.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2zyxofpwz.html

strcmp(a, b) == 0
来源：http://dali.svipenyu.cn/Article/details/gt2udwpfbqe.html

[S07] C：数组遍历求和
来源：http://dali.yueranfly.top/Article/details/gt2gvzydtkj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gt2wvxwpdsq.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gt2ewpymgfg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2ggnvjfgy.html

[S09] C：结构体定义与初始化
来源：http://dali.gotoacloud.top/Article/details/gt2tzjxxrqz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2qydthrin.html

[S10] C：指针与解引用
来源：http://dali.guowangkeji.top/Article/details/gt2jlocnfjo.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gt2tyaemqmh.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gt2wqkexald.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gt2mkxqwvqu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gt2dixuvswh.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2dexstcxf.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gt2vuoqcngu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cheryme.top/Article/details/gt2uqowvojb.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gt2weihdnkb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2slzekjeh.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gt2hrkoeiwi.html


<!-- 参考信息 -->