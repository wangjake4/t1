代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.wangshuangyany.cn/Article/details/gt2huuhlxwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gt2crshwokb.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gt2iupafvxd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlygpmjt.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gt2srulzdqe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gt2ndyvwvdk.html

[Q45] EXISTS 判断存在
来源：http://dali.cdnleiting.top/Article/details/gt2nrgxtlkw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gt2onmlzdrz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gt2ihecmxzi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gt2utxqdsvb.html

[Q47] 与平均值比较
来源：http://dali.9152youxi.cn/Article/details/gt2jchupzfg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhiwuduotai.top/Article/details/gt2juaqxqoh.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2yfxvctzz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gt2ohuqlnmw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gt2xexzsaos.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gt2oapznuzd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2glndadpr.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gt2fmbnhnui.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2uwgicdsh.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jymmnfec.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2gafhiimt.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gt2gfpjiulu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2fmczeciw.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gt2svymkbna.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eipjnezw.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gt2qtvsrvbe.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gt2mjjievso.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gt2admezlpp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2yytmgtpt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gt2hlmtlnjw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2gazoogst.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gt2yprctuot.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2wtpejlnv.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gt2adfswcpx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gt2ymbuxvcu.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gt2bjcaagyb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryncgavu.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwfgpqku.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyhjpwbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2jyaxeilc.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2hoarhsnf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjipmkly.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gt2ccdsuqzk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gt2yijzcirp.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kzszpyqh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gt2dpwevhsy.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfasblfo.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gt2jhwbjpyo.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gt2kuaskayq.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gt2rnlwvrvh.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gt2upxrhvyw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gt2ftpdfoti.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gt2tmwordjp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cucudq.cn/Article/details/gt2ivvusyzp.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gt2hctnhwar.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gt2igucmokt.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gt2jedhunrp.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2mbpihkiz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gt2rziadfbi.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtlhqsgd.html

ANALYZE TABLE users;
来源：http://dali.ivvv.top/Article/details/gt2kjqffuin.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2enpsudxh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gt2dvajdanv.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2bfglgqxo.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gt2rnyjnlzj.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qexsxuzy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gt2neyvjpbo.html

[Q74] 强制使用索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2anbnuqvm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2tgjdmwuh.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2umrwzccn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2ksjisvhh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gt2tpzcbgdr.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvusdiuz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2svggvmun.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gt2mrjvesuh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcjncdbn.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gt2pmhzogqc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gt2jnmxvqyk.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gt2lrguyamr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gt2uewadahc.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gt2nluxvsff.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqdyuvgc.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2wztcatmd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2ikogpvej.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2slnfktod.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2rjtqxiia.html

[Q83] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gt2rawstoee.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2tfjqxhod.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gt2yrfouyun.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2mqhbjwzr.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gt2gmxxdwrt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gt2ngnoswki.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gt2fywabhzf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yj20258.top/Article/details/gt2okshaeqv.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gt2spmyyaxb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gt2uihoqbyd.html

[Q88] 行转列（条件聚合）
来源：http://dali.mhx1999.top/Article/details/gt2bxtealpu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gt2shxqnlmn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2kuspbtmc.html

[Q89] 判断表是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2nylfryok.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhiwuduotai.top/Article/details/gt2uupjsceo.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkfmruyl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gt2ubdzhyoj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2iszgpibz.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gt2bjcvhnzv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iezfxaki.html

[R01] shebang 与严格模式
来源：http://dali.daria6918.cn/Article/details/gt2lomvicvw.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gt2rygugqxm.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gt2myxdarjo.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2sjjtydtb.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gt2yelznfgz.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmscddyd.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gt2afrpfxyy.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gt2qihtsmgz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlcfsnm.html

[R05] 参数默认值
来源：http://dali.ydzc1.top/Article/details/gt2qvmtfukv.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2kzirkrot.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uozkphvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2rwfbspit.html

[R07] if 判断文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajlteqsg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2txhaxxpg.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gt2bkdxwqaj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2owjbfetf.html

[R09] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gt2djfurmxy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gt2iqjqyaik.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gt2razmejeo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2saxaddfe.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gt2dhhvcheb.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gt2cuvhrfhb.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gt2cmmzcrwv.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gt2mkkrrwmm.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gt2akriripu.html

esac
来源：http://dali.chenzaomai.com/Article/details/gt2emsmflbq.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gt2qfbzcjwg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhixingplan.top/Article/details/gt2ropwnqin.html

[R13] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2wwriuceh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2hzhxmdgq.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gt2gesuwuvb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2jomjppws.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2nkjkopmg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gt2fjxglldp.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gt2kdhkxpqa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gt2xjfkqrof.html

[R17] 数组定义与取值
来源：http://dali.jiagoushi.top/Article/details/gt2krfqrlbo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlyjdzoh.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gt2fekbdolx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tianlin.xyz/Article/details/gt2lwyninlt.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gt2efinwotp.html

echo "${#arr[@]}"
来源：http://dali.cdnleiting.top/Article/details/gt2gajaedzh.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gt2puihiksu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2yicygrml.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gt2tpczzkua.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gt2cxesrnro.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gt2bumiqxnb.html

echo "${s:0:5}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcnmfzpu.html

[R23] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2bsxstzhk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ivvv.top/Article/details/gt2hgyxddmt.html

[R24] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gt2dfrjfyui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gt2cqyrxqym.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gt2wrcckevc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2ssovzjwx.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkkudgim.html

now=$(date +%F); echo "$now"
来源：http://dali.birdmap.top/Article/details/gt2qsegvqnh.html

[R27] 算术展开
来源：http://dali.sysykeji.top/Article/details/gt2fhoznxjs.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2dptklbhb.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gt2mcnnqvxj.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gt2nyrwlbvz.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2sybmhsjc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2bbhwkuqm.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2henesfsy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gt2kzrlzxkz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bueojpxm.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gt2gkktltgc.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gt2vvxdgmbs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2iayvcead.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gt2cvcblmyn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gt2rqyygbnq.html

[R34] 退出时清理
来源：http://dali.ydzc1.top/Article/details/gt2vnjkhruu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2uxdfzxgr.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkpsmfnb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gt2dksoqjnr.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gt2kdensykf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gt2lzhomwur.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gt2twgkzncp.html

files=$(ls -1)
来源：http://dali.sxryk.cn/Article/details/gt2uglurgke.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gt2dwccyzdy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gt2pkvpixds.html

[R39] 重定向标准输出与错误
来源：http://dali.dashuyun.cn/Article/details/gt2rbvviddx.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2vzqeglzj.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2paclgezf.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gt2nvmeowuo.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gt2muslznlk.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gt2whwekybs.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gt2aruzjybo.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2oakksqnz.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gt2mpbdfmew.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ghrrzpbx.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbapzwpc.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gt2hdjsocdn.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gt2niapeooj.html

find . -name "*.tmp" -delete
来源：http://dali.cucudq.cn/Article/details/gt2ttkywkod.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gt2ldddwdlz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gt2mwhvkvof.html

[R47] sed 单行替换
来源：http://dali.jiagoushi.top/Article/details/gt2vyewojfj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gt2uzibjnvz.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhurjenq.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gt2acuhjnmr.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gt2nsvhkzpk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gt2wvbtrouc.html

[R50] awk 求和
来源：http://dali.jyoumei.cn/Article/details/gt2odyqtkfm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2enakbgkr.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gt2duxjxofg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dojgaubx.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gt2grmwcgjb.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2otuwogqt.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gt2fsctqqnx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gt2qbfcnwyr.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gt2ccyisdkj.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gt2oqvoboxg.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gt2rnhrawur.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xinyue.icu/Article/details/gt2zsujmsxx.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gt2gwkkqbvt.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gt2svuxvnqv.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gt2angmbyet.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2fqnvttmb.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2tplfjrwm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gt2qsckdbsi.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2geqaweiz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqsvkvsu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2dkgpxjrr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sxryk.cn/Article/details/gt2cpzqpjsr.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gt2lnkxpqjg.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gt2wdqceejq.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtpthdxo.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gt2jkxynabk.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gt2pylpfmwv.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2xrkgvtxd.html

[R64] 结束进程
来源：http://dali.yongpay.top/Article/details/gt2kkgqbqfo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.quarkkingdee.top/Article/details/gt2nbppdzvo.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajexlthe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gt2tetoxzln.html

[R66] 定时任务
来源：http://dali.sysykeji.top/Article/details/gt2egnkcsyl.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2xefpynwk.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gt2vfmgqpue.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nebxverq.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qvrayydq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aizwys.cn/Article/details/gt2yzkblnvx.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwjbfxft.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gt2sfttqxqy.html

[R70] 时间戳与互转
来源：http://dali.ivvv.top/Article/details/gt2aeylvwaz.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gt2kyftstoq.html

[R71] 日期格式化
来源：http://dali.bjfxy.top/Article/details/gt2nkwspbwe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2eqfgdpxm.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gt2zjszawcs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gt2utldtfkj.html

[R73] 分割大日志
来源：http://dali.zhoulong.xyz/Article/details/gt2nbaqhjsg.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gt2qlszshsm.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gt2dfwamxow.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gt2xzyhokjh.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gt2hdzlgxcf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2ywmlohtt.html

[R76] 使用临时文件
来源：http://dali.tianlin.xyz/Article/details/gt2zvsrmmcw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2xfszfcsb.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gt2wouqqopg.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gt2gfwzhsrm.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gt2rhwsvunv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gt2vdihbwxq.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gt2bitzzpgg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258888.top/Article/details/gt2kgraacgs.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gt2exileegk.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gt2udaepcuv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2hilmbivo.html

S. C / C++ 专题
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibrxmhag.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jljynkpk.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycnrjsir.html

#include <stdio.h>
来源：http://dali.hysaishi.cn/Article/details/gt2tazxwpix.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gt2verxagho.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gt2xureupjs.html

int a = 10; printf("%d\n", a);
来源：http://dali.iojbl.cn/Article/details/gt2ifsnqrkc.html

[S03] C：读入整数
来源：http://dali.jinqigufen.top/Article/details/gt2lacbrmol.html

int x; scanf("%d", &x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqijmews.html

[S04] C：字符串复制
来源：http://dali.hysaishi.cn/Article/details/gt2qjgpfjlw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2inzvvzke.html

[S05] C：字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gt2mvofhnqe.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gt2aimzjsrt.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2vfuaqkxa.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gt2wesvujfh.html

[S07] C：数组遍历求和
来源：http://dali.cdnleiting.top/Article/details/gt2zvcidojw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gt2fozwwwwu.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gt2pptbhhbn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gt2libzdnkx.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gt2mtvpniig.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2xeeskfby.html

[S10] C：指针与解引用
来源：http://dali.yj20258888.top/Article/details/gt2bgeegzgj.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gt2viykjnba.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gt2kdgmapqd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gt2cjklndkq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gt2zhxyxbkm.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gt2fpovhvtm.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gt2tfpcijpz.html


<!-- 参考信息 -->