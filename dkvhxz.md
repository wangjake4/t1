代发 wailian999

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtwabuzmkl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gtaugghhbk.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtcdpbyusf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtycsdwfei.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ybcxt.top/Article/details/gtzeawzvrs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtrkhfvjwi.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gthaonqyxv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aizwys.cn/Article/details/gttziytqsz.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gteppmbscw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gtjevephng.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guannengcc.top/Article/details/gtsnhrzmec.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtjbrtmkkw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtcnybtqlr.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtkhivawfd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprhbcafb.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtfgflpazc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtdnqxaxsx.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gtpbrmorse.html

DELETE FROM users WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtugtzjyig.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtnzvoabuc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunxcnhmm.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gtykaeofsq.html

TRUNCATE TABLE logs;
来源：http://dali.tian-w.cn/Article/details/gtkruawbew.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtllwzeyol.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtkkrzllkh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tianlin.xyz/Article/details/gtbntlvphf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtifrudvhf.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtqhnspdpl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daria6918.cn/Article/details/gtshxafcwa.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtrnnyaetq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtxzdrnsou.html

[Q59] 分组内累计
来源：http://dali.sweek.top/Article/details/gtloeutngs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtoyaloiiz.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gteixtandc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gtpxprqdxj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gttgnsacxz.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtigrwtiib.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtzgyldftb.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtjjzimpcc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gthpnfugqz.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtfoqjaezu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtqqzaabbh.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtymzegdqe.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtvferqxow.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtnieshjcn.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtyanvedlb.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtabptjczd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gttseidqsc.html

[Q67] 设置隔离级别
来源：http://dali.pycfn.com/Article/details/gtkajlyzpk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gttftwosqe.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gtzsttwnzw.html

SAVEPOINT sp1;
来源：http://dali.sufxvd.cn/Article/details/gthnsaydhu.html

ROLLBACK TO sp1;
来源：http://dali.cdnleiting.top/Article/details/gtswyqpzfs.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjzyspke.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gthwfziijl.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtqndgtbze.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtddpqmitr.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtkhzsfrxh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtkliexiqd.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtrmhaepca.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtivrpcxky.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtgvvwmcfw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtvmtnkasx.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtujcekfaj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtwatsnigl.html

[Q75] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtgdvmcdyq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtehggotxe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtxxoubdbf.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtzrhlxxqa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtucmanond.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gtkdlktzjh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkhygugn.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcgjqnsi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtkfanxfhj.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtgxpbhspj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtoprpkxex.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gtmcgzydix.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtfpiqnqne.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfwajxgn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guannengcc.top/Article/details/gttkwyppub.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtuykwhcsh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdulwomvt.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtrnvfpopv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtxesifual.html

[Q84] 去除首尾空格
来源：http://dali.xinyue.icu/Article/details/gtlhbmbnyf.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiwxsmsx.html

[Q85] 数值取整
来源：http://dali.smart0.xyz/Article/details/gtgutahgry.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenzaomai.com/Article/details/gtkbqttboq.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gteolgmmvl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtgvxwwzlw.html

[Q87] JSON 字段做条件
来源：http://dali.ydzc1.top/Article/details/gtosrwnvlj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuxming.cn/Article/details/gtevbdxkuj.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtwdsomxvz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtgohztkyy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtcmqmrygy.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtpfhjoeez.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtyyecmxka.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gttbhibwsy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtaiozpzzb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtidzgjovn.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gtopgkjrdn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gththbfxaf.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtwhbamsbr.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gteevlovfw.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtkunjccny.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gtblicogkh.html

name="Tom"; echo "$name"
来源：http://dali.aibaodan.cn/Article/details/gtbwkerkuh.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtjnicyhan.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtcrvybsjw.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqjreyvr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gtucrnnpnq.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtpmrzmorn.html

name="${1:-default}"
来源：http://dali.wangshuangyany.cn/Article/details/gtccqgwklt.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtstwhbevb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtloehtvnt.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtokltzuex.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtgddudbrv.html

[R08] 数值比较
来源：http://dali.yuxming.cn/Article/details/gtxupiatpo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtyygsvjdb.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gtajqymedw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtlzkuhtsk.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gtxgkkuiil.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtsoirjeoj.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtnytwdiuw.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtjwnioxel.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtkhlaacya.html

stop)  echo "停止" ;;
来源：http://dali.wangdashe.top/Article/details/gtxouklslf.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtxpkzwosm.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtyeycgmrf.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtreqvdilv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gtubzdhooy.html

[R13] for 计数循环
来源：http://dali.haohaochexian.top/Article/details/gtlnczagnl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtryzxzrdw.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtxruzgfmh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtaxlenddj.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gttcpjynrz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtonjygorq.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtfbzhhxnj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtvbesftdr.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtwiwcehei.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtdhhqdrck.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtklimyflq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yongpay.top/Article/details/gtqdjyoliy.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gthhvhaedc.html

echo "${#arr[@]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gttrclsvyk.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtwvbluwbp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtautsyubc.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtlepdbdhe.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtjgsjuvnt.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtnwmsplpu.html

echo "${s:0:5}"
来源：http://dali.birdmap.top/Article/details/gtpjempwdk.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtoooeapid.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gttggzewxy.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtdadniqqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtdtfecapd.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzftwywam.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daria6918.cn/Article/details/gttdxjzxwc.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gtptwnozwk.html

now=$(date +%F); echo "$now"
来源：http://dali.hammf.cn/Article/details/gtnqldahxa.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtkausyzij.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gtpoepyihb.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtskwkwenj.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtbmyfypmm.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtaujknrmf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtqwlzeltx.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtvwmmddla.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtmznpyrxy.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtjhjfldyy.html

f() { local x=1; echo "$x"; }
来源：http://dali.cashguo.top/Article/details/gtdkamsstk.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtizzkwnxu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gogol.net.cn/Article/details/gthnsdeqbj.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtbymlfsus.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtzmuegkfu.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtemfzwaov.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtomseoxqx.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljrntjaa.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtbuugvsks.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtyxigjesf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtuaxpfqlc.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtepcxuzsx.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqhalknj.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtmqayqghs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gtxswunkao.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtvfhldfap.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtgglfrewc.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtrvfgehtl.html

echo "log" >> out.log
来源：http://dali.yj20258.top/Article/details/gtebcxdumr.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gttsjflzbd.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtydrwmbvv.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtxhoncdyc.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtyjribxrw.html

[R43] 按名字查找文件
来源：http://dali.zhoulong.xyz/Article/details/gtbtvwzpqj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtaodmkaam.html

[R44] 按修改时间查找
来源：http://dali.dianchejie.cn/Article/details/gtothoztad.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtcpjzjfef.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtptheprtw.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtsgixuevm.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtcvioxdjz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtxetjvvjs.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtrmyhdxoc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtfutizudm.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtlattpwfm.html

awk '{print $1, $3}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtwcfutgtt.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtwxmbxmfc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtoghlcmar.html

[R50] awk 求和
来源：http://dali.kuanghao11.cn/Article/details/gturhromtn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtnatrankw.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxoqtozf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtjckklxsv.html

[R52] 统计行数
来源：http://dali.gotoacloud.top/Article/details/gtcxdhlgul.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtfmfzckpl.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtwdwuwgzw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtnlvwicwl.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtlvtzttfm.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gtjyneuevh.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjufkzsb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtqkssafcu.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtkbeoirma.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtahrpljxv.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtarhypeth.html

ssh user@host 'uptime'
来源：http://dali.yj20258888.top/Article/details/gtwhzklptu.html

[R58] 下载文件
来源：http://dali.meibo888.top/Article/details/gtmyyncqmg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtpykpmxrt.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtewqcfssz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtspcczmwj.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gttzrwzwqt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtkfqrxjho.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtcqkqfpyo.html

df -h;  du -sh *
来源：http://dali.chenzaomai.com/Article/details/gtcgaqonlt.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtnloudfak.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtsgxkpwsb.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtmemeoxmb.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtuqcuuboy.html

[R64] 结束进程
来源：http://dali.aibaodan.cn/Article/details/gtyufhpqzv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtbivggcui.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhejrzzx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtgqfqrpys.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtqesaosqu.html

crontab -e;  crontab -l
来源：http://dali.tianlin.xyz/Article/details/gthkscmvbu.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetwwdzgs.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtjwbumequ.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtbacojzlg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtcfpufogp.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtkonbksss.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtkojqyjmf.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtlakjlf.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtfayrqsug.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtstkiifuz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmpjnapq.html

[R72] 等待端口就绪
来源：http://dali.havefunace.top/Article/details/gtgwqxxfjz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtauefvilj.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumfyvvrc.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtvublxoeu.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxncpmtqu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ivvv.top/Article/details/gtobbwniup.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtpmhjtpmh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtjpzbbhku.html

[R76] 使用临时文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnnxwpus.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtiglqssge.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtztmhanyk.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gtekdbngan.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqtgyfgc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtkjkxaucm.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgmewbsl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtnskfienv.html

[R80] 查看脚本执行耗时
来源：http://dali.iojbl.cn/Article/details/gtehqweict.html

time ./run.sh
来源：http://dali.hammf.cn/Article/details/gthxdjhkjf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnblohhgc.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtwqqajuns.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaictjqyk.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtkjlmsgdt.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gtnnuxcsxg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtsidcxrqa.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltfvmkbq.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtsraxefxf.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtaygvfzga.html

int x; scanf("%d", &x);
来源：http://dali.yonumen.top/Article/details/gtxacygwkp.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtbvrcmizw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiyonsbn.html

[S05] C：字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtkmugoyyv.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtfunpvixi.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtcjcedbap.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtxyyckbqy.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarlejuwc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtcwljusaf.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gtjbukqxxh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtavmoxiyw.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtlhudbcor.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gtmoubqttq.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gterxqeflm.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gtpuiekbwk.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtvdrcskxt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtmhzeqxfp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gttymnhajo.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtyvqgojqf.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtmrurdkdy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtybsikixz.html

[S13] C：宏定义
来源：http://dali.fengsongda.top/Article/details/gtfdkhngdy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtbzmtpxdw.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtogoapgka.html


<!-- 参考信息 -->