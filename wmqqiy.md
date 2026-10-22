代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2hjaqmnzt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fzhhl.top/Article/details/gt2kiwgtfqa.html

[Q39] 自连接（查上下级）
来源：http://dali.tianlin.xyz/Article/details/gt2khtuixkv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gt2hjhwqmzc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gt2eouehazy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.andypj.xyz/Article/details/gt2gxlaqqtk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ogryhhnk.html

[Q41] 多表连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzpvrrur.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gt2vowxbosv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gt2sfcgqglf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2hkeiidiq.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gt2iewwupph.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gt2umktlufx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gt2couyxric.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gt2zfbeyjmv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gt2wgrwoena.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gt2ptjsfphy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gt2fmohttnh.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmvgliyw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gt2fnkwavqj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnjnneqt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2jnyawnuq.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gt2qlahlznm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gt2reruiqgk.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gt2iekuueik.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gt2msqwabxg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gt2ovpudpoh.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gt2ihpcmzew.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2tdopxtwo.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gt2liwmjjna.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2mmfhvjry.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gt2djhcikxq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gt2cpvghqmq.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kytxknre.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gt2fsyxjdpv.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gt2uxytyrym.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gt2hytzacyg.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gt2ictvusfr.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gt2secodync.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzflnhmv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2czgpwfub.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucztsznz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gt2dosnjeyp.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gt2okpuimbl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gt2ddgczrgn.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2lqvfbksi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2fnniniwn.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gt2ghjoujlu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkakeczi.html

[Q60] 取上一行 / 下一行
来源：http://dali.guowangkeji.top/Article/details/gt2koobkdmp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gt2qbhhbcsv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2sqenlqgk.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gt2wqfucijs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2zmsmdgno.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gt2wjfslpqa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2txollcev.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gt2qiqpqntu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gt2uxizgssx.html

[Q64] 提交事务
来源：http://dali.quarkkingdee.top/Article/details/gt2nvorwgfi.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2wzlrtgvv.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2harbsuyt.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gt2akavtpxv.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gt2kufipiwy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gt2sjznjbls.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gt2muprmstc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gt2krazgcmg.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2xtnkyeqg.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gt2vpoldkyd.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gt2dncfbatz.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gt2zjzqousr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2amueghei.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2pmexfruz.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gt2ozoyiprr.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2vpivmpes.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shuidangran.top/Article/details/gt2eajszspa.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gt2ekjzfeep.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gt2bxgowlfm.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ozaaazrr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gt2mwkdqcfd.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2jwcgqbkp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gt2cwlzonnm.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2lhyiyrvk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yognvpam.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gt2tazibqhe.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2fbqoqjkk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gt2dpspqlxv.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gt2pqerivtd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilnxixuf.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gt2cjskmhhf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gt2kukgqcig.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2mlusqbsq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gt2frykudiw.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gt2zmffuyyx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqkcyrjk.html

[Q81] 字符串替换
来源：http://dali.jyoumei.cn/Article/details/gt2fcbbmsyi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2nednoxpm.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gt2dfdpwhqp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2zbakpims.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2kpqtkfay.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2djoofcnl.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gt2ehjaupbx.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2tiyhlkmc.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gt2mdswznwm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gt2rhxcckuy.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gt2saxcwsvn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gt2utixyggg.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gt2sdxgibgx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ehwqpu.com/Article/details/gt2wdikpsue.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2nrhxwtdo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gt2isilhwpe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2qomvofee.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocwjftpz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gt2tsrcvgrq.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlyvfjez.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2gkiovkam.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2nkzsnhsh.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gt2nwmgmemj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2tbguzvtt.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gt2jbuyvsnt.html

#!/usr/bin/env bash
来源：http://dali.svipenyu.cn/Article/details/gt2kthmbvet.html

set -euo pipefail
来源：http://dali.dianchejie.cn/Article/details/gt2xdvojvsh.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gt2gytbiucl.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2acuokidd.html

[R03] 只读变量
来源：http://dali.cucudq.cn/Article/details/gt2tiaevqtl.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gt2mulatstn.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gt2yynzzizg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gt2idvjbays.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gt2yaosocug.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gt2sfhflgia.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxgwtoyq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2oeuhqxfw.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gt2aaqfvwwo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icjxjpgg.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gt2ugxoyppf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gt2qdseqonz.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2fhfedpcq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gt2gbvbsfhm.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2vqomgzju.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2fnaeghwj.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gt2hxyljufc.html

case "$1" in
来源：http://dali.ybcxt.top/Article/details/gt2dwwtoplh.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gt2bbkiukdr.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gt2ipbdefox.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gt2mrsqpwjw.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gt2xtozodag.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gt2kxodkxbw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlswxqpq.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gt2fjadpmzw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2zpuuvouw.html

[R14] C 风格 for
来源：http://dali.tanke756.top/Article/details/gt2vpvnxioc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2eouongdb.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gt2npmkbidx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gotoacloud.top/Article/details/gt2ztimfmfp.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2uuxqzysx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2wgnfnxek.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gt2sqjgulyy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2hsqtypwm.html

[R18] 遍历数组
来源：http://dali.zhixingplan.top/Article/details/gt2tkoigrdx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gt2fxdblpqi.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gt2brbqdolc.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gt2jabyuans.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gt2kscpklmz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gt2ttqatzpa.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2dsbhcgqk.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gt2zpcxblla.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2rnxrzgbr.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nghdmici.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2bqzhelsf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenjidiqi.icu/Article/details/gt2itwupgjp.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2lmyukkvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gt2wjubwpdc.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2raiotowc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sweek.top/Article/details/gt2fvkrsmro.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gt2lycilfuk.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258.top/Article/details/gt2ekyhsell.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ephlyjrs.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gt2kfkarueo.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2sahknxwb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gt2ezqnfasj.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjyzqaaw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cashguo.top/Article/details/gt2olouacqj.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvvotubn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gt2znzmivpl.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2kbacdhpb.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kovptdpf.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gt2vabmxxlk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gt2drcfjcmp.html

[R33] 捕获错误并提示行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fzxabmzm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qoxvszxt.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gt2gxgbhqnf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gt2vszpkgqe.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gt2oejotjlf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gt2jcmvrxct.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jhuxaalf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2vfarxinx.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gt2kbanrmfl.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gt2cjoqibtt.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gt2csalqyeb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gt2kfrljsoa.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gt2bgsunvma.html

cmd > out.log 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gt2wpdnccbk.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gt2skofoqll.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elfrrxjz.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qovozmun.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gt2uvarsaeh.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gt2zepqinvm.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2pwqjfvtn.html

[R43] 按名字查找文件
来源：http://dali.cheryme.top/Article/details/gt2cycxwhtg.html

find . -name "*.log" -type f
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtoncbzn.html

[R44] 按修改时间查找
来源：http://dali.gotoacloud.top/Article/details/gt2cbcytqop.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gt2wjdrvljg.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnzhatvl.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2fpjbqqxl.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2dpndvvmv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2cnyvqaus.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gt2xacjmkhw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2wplwgifp.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gt2fgkgmzdm.html

awk '{print $1, $3}' a.txt
来源：http://dali.316326.xyz/Article/details/gt2efhvnqjd.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gt2ynkwwxmd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gt2pvsqtelv.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gt2btahmvtj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2enmfrkbo.html

[R51] 排序去重取前几
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drumphjf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2dfvnrrgb.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gt2cmlpgrgv.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2vylwqvqp.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gt2vrxnemyb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gt2nseooiul.html

[R54] 比较两个文件
来源：http://dali.smart0.xyz/Article/details/gt2gpavpkwb.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbyrxweb.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gt2ltnqbuwc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gt2ylccxmwi.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gt2gjlrikqe.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gt2lnjodwzq.html

[R57] 远程执行命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjlxqecx.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2rayxqspi.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gt2qyfhwstl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbelwxap.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2zduacomv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2vwtlolhd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twvfcaes.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gt2bokaxbsz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpvccbp.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gt2bjroefxd.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gt2zuwgalyj.html

du -ah . | sort -rh | head -10
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdybgakz.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gt2wknhrwyr.html

free -h;  ps aux | grep nginx
来源：http://dali.zhoulong.xyz/Article/details/gt2wdspzthq.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gt2jrcefyop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2epyrxzbw.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gt2pftslmid.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gt2dinlbhbg.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gt2sxunlpur.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2hpkvrnoq.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gt2uccriqqu.html

openssl rand -hex 16
来源：http://dali.hnqzz.top/Article/details/gt2uqdbikae.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gt2qylpzxhs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2rjyaojok.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gt2kjomtqsm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hammf.cn/Article/details/gt2gwawldln.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gt2gnmglsft.html

date +%s;  date -d @1700000000
来源：http://dali.tianlin.xyz/Article/details/gt2ezutuutk.html

[R71] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwgfssfw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gt2tghhghde.html

[R72] 等待端口就绪
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fctkaxvw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2almttsdb.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gt2nlubjope.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gt2rknolpia.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gt2taznpnzy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gt2xgpeemxa.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2ahzsgacj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gt2vqttwifs.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gt2hkbfdrlw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2ayoqttmo.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxkesfyd.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gt2mgnkfqbv.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gt2wxeaazwu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2cjgesgzg.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2izvryokd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gt2iifnfoel.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gt2ygfshigj.html

time ./run.sh
来源：http://dali.yvedp.cn/Article/details/gt2jmdbyfqf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xptqgazh.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gt2wtwtqsgk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lurggwdp.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2fprxdegm.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gt2ukpfhwyv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gt2ahjvkzjp.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2qppzrpma.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gt2zkawpmkt.html

[S03] C：读入整数
来源：http://dali.feifeiyinyue.top/Article/details/gt2ggnqneqo.html

int x; scanf("%d", &x);
来源：http://dali.xuanzx.com/Article/details/gt2pdyieovu.html

[S04] C：字符串复制
来源：http://dali.c1oappe.top/Article/details/gt2hhwcgpkk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2ukwfawjq.html

[S05] C：字符串长度
来源：http://dali.tian-w.cn/Article/details/gt2dvirfsid.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugndltrr.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gt2dleifeua.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gt2szpxzyhc.html

[S07] C：数组遍历求和
来源：http://dali.tanke756.top/Article/details/gt2mdpiruah.html


<!-- 参考信息 -->