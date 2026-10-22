代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gt2kfepznwx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gt2zsvdtnji.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gt2ymgdwneb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2uwnldqpc.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gt2cyfseohy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gt2bgvaoewy.html

[Q45] EXISTS 判断存在
来源：http://dali.cashguo.top/Article/details/gt2khagusix.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnxiangtu.top/Article/details/gt2kacazqjq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gt2stfzksdn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gt2kpnmiexg.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gt2fyfzuhkw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lavwhoef.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gt2dmxgmwzz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gt2abemktpz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gt2lgjjsith.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gt2cnhotnxq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orbovzug.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2srwcryor.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gt2vyympult.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gt2mibrgzbn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gt2rqkapfrn.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gt2odkewjaz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2mswvuvfy.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gt2aheaxcmi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2hvpjnycv.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gt2icfzvqlv.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gt2brbzjfmq.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gt2fzfuypic.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2jntjmegx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2qsxkpbnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2anblwiap.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gt2qvjmwpsl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2bkvoixei.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gt2ahjweefk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2yonjubhn.html

[Q59] 分组内累计
来源：http://dali.gaohongyu789.top/Article/details/gt2pofjuwea.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2lappausc.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gt2cpnpgaqk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gt2nveoddbg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2hqdrrvus.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2ymdowndk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2wksigbse.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gt2ujpojdnx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxovgtig.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gt2qtwnwoci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zndoqfjx.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gt2hnwjabei.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gt2olcmaikz.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gt2gobtenhd.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2ufrziobt.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gt2bhpyrspt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gt2pewhnyju.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2uahcpazl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2ehvlozin.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gt2mlmhosgs.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gt2jmastmcx.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gt2vfyhvbbw.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gt2fhlqgqmq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gt2zprzvkyh.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gt2nrrvtlwf.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gt2jkvxyull.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gt2neojxggk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gt2ekhnsxlq.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gt2igkchzvl.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2lbqbzuht.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gt2uenwuoad.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gt2eelqfueu.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gt2dyufyoyi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2axhlarat.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gt2wdaztvon.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2fyehbvpv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hammf.cn/Article/details/gt2mxntjqwu.html

[Q76] 按天统计
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qitczois.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gt2evctydnz.html

[Q77] 时间加减
来源：http://dali.hnxiangtu.top/Article/details/gt2nxufrlfm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgfzy.top/Article/details/gt2dkejflgq.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2jyhvocvs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gt2tnqziwbh.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2dyfetsax.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gt2yuxjitql.html

[Q80] 字符串截取
来源：http://dali.hysaishi.cn/Article/details/gt2vrxpqdue.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2jpgohzwd.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2bkodmqcq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2jrosnbet.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gt2sukgvcsx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2eypecdxp.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2cwywqszp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2dfsblyol.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2rmajwtjk.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2rsghwpts.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gt2bzlzntuz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhongyouzk.top/Article/details/gt2uvchghjm.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvlkiujw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gt2vvorqqau.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gt2rfuvpits.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2feuzrrhe.html

[Q88] 行转列（条件聚合）
来源：http://dali.sysykeji.top/Article/details/gt2llvqrcnj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.mhx1999.top/Article/details/gt2tczjtafc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2qcfrqrdz.html

[Q89] 判断表是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ylsgsrma.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2mhbtpswi.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2zsdnldko.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxoewjzl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2phgbdduy.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gt2apmxquht.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2hbnnwfxo.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gt2jxvgswxp.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2ccbgzadm.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gt2oxcojdzf.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gt2qpkvacux.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffawsmpf.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gt2fjxnvjkz.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gt2bvvfzykr.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gt2sgfirwxm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jyoumei.cn/Article/details/gt2zizoxhtu.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2kxyqvjvq.html

name="${1:-default}"
来源：http://dali.sxryk.cn/Article/details/gt2mfzodhll.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2iffcnnbs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2zhuzywyb.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gt2oxvwfwyx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2uittldkb.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gt2mcfzhjjc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2olrbunfo.html

[R09] 字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gt2sgekubyy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2vlfgmhwh.html

[R10] 正则匹配
来源：http://dali.zdqjudy.top/Article/details/gt2nblolnuv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gt2wwblecjb.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2ompkvzok.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2dyrxldaw.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gt2akpeoyla.html

stop)  echo "停止" ;;
来源：http://dali.hysaishi.cn/Article/details/gt2pixgidxw.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gt2veubvjme.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2ctvgjcof.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gt2mzddcion.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gt2xnhfjsxq.html

[R13] for 计数循环
来源：http://dali.ppjwa.cn/Article/details/gt2wyhbyiro.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2traambgs.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2fdddivsp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2oknopezn.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xchmrilq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gt2vnwajnbv.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2kxdyigzg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gt2wjwtuwrd.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gt2zwlafpqd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yengelgu.html

[R18] 遍历数组
来源：http://dali.kuanghao11.cn/Article/details/gt2sqbbcljw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gt2vnumotov.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2kiqxelly.html

echo "${#arr[@]}"
来源：http://dali.ydzc1.top/Article/details/gt2izlxnbki.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gt2kqdzikmw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2btyyrruo.html

[R21] 字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2cfuuhswe.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gt2psbqfrix.html

[R22] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efvtxqye.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gt2tezknxvi.html

[R23] 字符串替换
来源：http://dali.meibo888.top/Article/details/gt2zabkutxd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmjanrxq.html

[R24] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2kmqpwoxq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzufckmj.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gt2wqcoyahe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2mgtfqqlm.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gt2jyhffhhq.html

now=$(date +%F); echo "$now"
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkworrry.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gt2cmeueqhq.html

echo $((1 + 2 * 3))
来源：http://dali.quarkkingdee.top/Article/details/gt2nwcstgub.html

[R28] 浮点运算
来源：http://dali.dianchejie.cn/Article/details/gt2dmxvgmoo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yuanzhike.top/Article/details/gt2mnvebwos.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hgiehijx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gt2bvshcnuu.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gt2patvhnng.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gt2axdwzjse.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gt2ehsyxjnn.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2eqmpvahg.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gt2zcrngzba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gt2zpwwwqxx.html

[R33] 捕获错误并提示行号
来源：http://dali.aibaodan.cn/Article/details/gt2apkigksx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gt2tvtyuxrh.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gt2jgckczwy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2xelooask.html

[R35] 后台执行并等待
来源：http://dali.guowangkeji.top/Article/details/gt2wfxlgope.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2saawudfn.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gt2vqwmgahf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gt2lmgbqzgh.html

[R37] 把输出赋给变量
来源：http://dali.birdmap.top/Article/details/gt2zbexbetv.html

files=$(ls -1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2duiwqnha.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gt2jxqpoahs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.pengpengdd.cyou/Article/details/gt2xdufiewu.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gt2rozbtrxv.html

cmd > out.log 2>&1
来源：http://dali.tian-w.cn/Article/details/gt2qemlkidh.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gt2urjqqags.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gt2klbmirur.html

[R41] 丢弃输出
来源：http://dali.316326.xyz/Article/details/gt2laiohgnv.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gt2nidbnfqt.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gt2hepgdclj.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bvhqpckl.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gt2lfjfbyqj.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2chthcekn.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivlqoubf.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2qsfynioe.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pxgnlqlf.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gt2sylnhqtp.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gt2wmdwzhmn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gt2tlgapnbh.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gt2udnkylfv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gt2qhaqcmco.html

[R48] awk 取指定列
来源：http://dali.xylfe.cn/Article/details/gt2pehpslbg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2zzinhhef.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gt2krjnivbw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yanxiufei.cn/Article/details/gt2fqqieyfa.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gt2dwbjkbxa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2mencgctx.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpuodkos.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndsfljgr.html

[R52] 统计行数
来源：http://dali.cqqwz.cn/Article/details/gt2eeunkcyp.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gt2ngfruitj.html

[R53] 查看文件头与实时尾
来源：http://dali.svipenyu.cn/Article/details/gt2ihghxbiy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yonumen.top/Article/details/gt2qyvaxdrp.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gt2fkqeffav.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gt2ehhvsbbt.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gt2buoqqetx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gt2jvbhjchr.html

[R56] 远程拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2hgkpjrlm.html

scp file user@host:/path/
来源：http://dali.jqgufenzy.top/Article/details/gt2obpqniun.html

[R57] 远程执行命令
来源：http://dali.jinqigufen.top/Article/details/gt2xfiupttn.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gt2ayxpeuuy.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gt2glqynmli.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gt2niasryqw.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gt2pvalsrim.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gt2qxvmbcnw.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gt2vvpbdgde.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gt2eidrftrb.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gt2rikeritx.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixscbtsi.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gt2zlykuygg.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gt2lekyahba.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbacbjda.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvnklzmm.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gt2flcnvwde.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigufen.top/Article/details/gt2wymlkidx.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2qouglrai.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gt2gyjyoimw.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2uzzbdmvb.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ytydqjzt.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gt2nkznkoyr.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gt2fctedlxx.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gt2csnpdniy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gt2wtatmlft.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gt2cbcvspip.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gt2fqlagjgd.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gt2kxxclwqv.html

date +%s;  date -d @1700000000
来源：http://dali.xinyue.icu/Article/details/gt2ksxiuqyo.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gt2gcwraaxv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gt2erwdsdgu.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gt2roqjktlr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gt2kwbrlzjp.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbpnbhnm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbwhnnm.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gt2vmseytkp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvjekidw.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gt2hvbmffch.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2eurtrgvl.html

[R76] 使用临时文件
来源：http://dali.redwolf501.top/Article/details/gt2abwofodg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gt2winlujfl.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgiigrwl.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gt2xrsrwmnb.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gt2uedrbixd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gt2trdjntsr.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gt2auyjxpdw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gt2dfnwkmig.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gt2laqkvcfx.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gt2lemgfjxo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2dpbccwll.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzudujso.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2dbhpmugl.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2zxtizyvg.html

#include <stdio.h>
来源：http://dali.tian-w.cn/Article/details/gt2gvzfpdiw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2vutczfwf.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gt2ymkyrlnj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gt2totgywsr.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gt2jozwsuje.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gt2hozyljdf.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gt2rgyogbap.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2pbhzghpb.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2stqldjou.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gt2bawdhhed.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gt2zyzhpztq.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gt2eitfwcfa.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gt2zqlkcqvs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gt2tvfojtsr.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gt2ivzqdscs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gt2qrcroody.html

[S09] C：结构体定义与初始化
来源：http://dali.kuanghao11.cn/Article/details/gt2chflrunl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gt2qjpurnyh.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gt2loermvfk.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gt2fdmudxmy.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2fytkuupn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxinkj.top/Article/details/gt2fgqbquxl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gt2eaikshnf.html

fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gt2mnpsqqaf.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gt2ttculfus.html


<!-- 参考信息 -->