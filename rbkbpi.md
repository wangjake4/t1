代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.birdmap.top/Article/details/gtqsdgcqgv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtzzouoltc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gtgygsjnrt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtxfcfditg.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gtkyzwffzt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtgdbvbkiv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtaoknzatu.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtdgaobhux.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtmujhtlwr.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtjtxymwjj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gtzzvdiocm.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtlimwqzli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtvjrnpfve.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtahnegfxn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gthkrivoaj.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtesgqdfbj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtafwqrfuu.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtbeilmxbt.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtmtcvppmx.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtiufoftgy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtxmeiyzhl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtufpnbyqc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtmctgbwqa.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gtdmrzzxwv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtedgqspjh.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtpxvhibvd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtjkanspaw.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gtkibigkgx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtszqpsrqa.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtfnltmlfr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtbhionxax.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtbqyauuds.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtswnanzll.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtwjjqdiea.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtmcevwkcn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gttufplyjx.html

[Q63] 开启事务
来源：http://dali.quarkkingdee.top/Article/details/gtskxscfrr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtndurrcmk.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gtrmsejeje.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtuiigemrh.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtwhluzncd.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtybiowunz.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gtiydtkado.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtvbdirjcd.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtyjccbhve.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtitzlwtwu.html

[Q68] 保存点
来源：http://dali.xuetiantiany.cn/Article/details/gtudsrzthl.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlazsjav.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gttbrqdxyi.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gtibhgvagb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtvublsprk.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtxrxigmos.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtndyoclgw.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtppwpaydo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtxzcjuboh.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtruwwdnri.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gtcvhwbsti.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtzqcytwxt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258.top/Article/details/gthuqtvttf.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gthpiijipt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxinkj.top/Article/details/gteqndreqk.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtbckjyjvj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtootdkyct.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtpzirkxmz.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtzfaaiiyi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtiimbguqg.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtbrqcpmcv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtkebsnpne.html

[Q78] 当前时间
来源：http://dali.hysaishi.cn/Article/details/gtltyxjgka.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtgzxmkqyo.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtvpnwritk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gtletwfymf.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gthstqrocy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtoejqpfef.html

[Q81] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtufvplsxa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.meibo888.top/Article/details/gtppplzkua.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghmpxnvz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtvwdrefdt.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtvfogrfbd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtgowujsks.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtfbdwsslo.html

SELECT TRIM(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtwghmzljd.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtsoqkioyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtkgaptheh.html

[Q86] 读取 JSON 字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnarthqex.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtcwvfeufh.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtknnkdjad.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtyojqessl.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtoqkkoklr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtckpiuozf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtohwxjvcr.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtbooiysac.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gteyrsupyt.html

[Q90] 生成序号列
来源：http://dali.hysaishi.cn/Article/details/gtkcalitbh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtbygqitdm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrlgpungh.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gthukuydkg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuoobvhex.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gteknmxilc.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtzwlafoxj.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtprbcaxtj.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabeqqgiu.html

name="Tom"; echo "$name"
来源：http://dali.yj202588.top/Article/details/gteuisyqyr.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtowqmuyxk.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtbzwpzyku.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtrtasvrld.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtemnsbmao.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtyorlpdzc.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtsdyavkfl.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtgqorgcnf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtktvnjrts.html

[R07] if 判断文件
来源：http://dali.vqdsnc.cn/Article/details/gtibukkcrz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtliagmwaz.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gtosfjdjfy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gthobcoemc.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtpbbgbfnj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtbxrhkxvj.html

[R10] 正则匹配
来源：http://dali.c1oappe.top/Article/details/gtpeavlsqa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.c1oappe.top/Article/details/gtbkjgascj.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gtfmyhfnfb.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyghcczq.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtumbvlazw.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtnfvrndgi.html

*)     echo "未知命令" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtlhiithud.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtrvzeiwpl.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtaxjicoog.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sweek.top/Article/details/gtsazkvuzd.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtigolhfau.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtjdtyagqn.html

[R14] C 风格 for
来源：http://dali.jqgufenzy.top/Article/details/gtwdhtcxeb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqycvftpn.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtbqsvlvps.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtkqkhzmgi.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtjfdqoccp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gtoblctrci.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gtwrgjujti.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gttduevors.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gtkbylahkf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtpxtpbqiu.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtbulvzobv.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtziakfdhk.html

[R20] 关联数组（字典）
来源：http://dali.zhoulong.xyz/Article/details/gtlhuxkucv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtleuzikco.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtbypqgaja.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gtfwxsamcy.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtxnazsfro.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gthfurgxuy.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtqzdwlswt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gtuobhqdtr.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtyticxdzn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yvedp.cn/Article/details/gtagxdqjpm.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtmaxgtuqx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gtkvuwwsej.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtgvjyhkaa.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtfqjypiba.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtrjarcvnw.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gttpsgneev.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtknnczwnl.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtdmhohvmr.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtfwjjhgfg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmeijqltk.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtvzqklnea.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwcfmjfg.html

[R31] 局部变量
来源：http://dali.gotoacloud.top/Article/details/gtwnodvpzc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtigtobnwx.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvohbxygu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtzbhcbwfa.html

[R33] 捕获错误并提示行号
来源：http://dali.ehwqpu.com/Article/details/gtlzxqnugr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtnxyajedk.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtgprtrizc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtwzflqfrg.html

[R35] 后台执行并等待
来源：http://dali.zdqjudy.top/Article/details/gtkbngkkua.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtvleazzfu.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtyymidmng.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtpmfmemef.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gtyewtuato.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtofyfoeeg.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtomsurexk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglzsizvi.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtlheqfuyc.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtgytohttv.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtozbzqjbo.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gtmhlemyve.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gteomvwwox.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtgtsectzo.html

[R42] 输入重定向
来源：http://dali.jinqigufen.top/Article/details/gtoukrqugu.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gtscgastqw.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtkshkzoqr.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtwpiaucss.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtjolqreor.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtnmbbnblk.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtlypvubbw.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtvujjtszv.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gtafdqdpcm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ppjwa.cn/Article/details/gtvidlyiur.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtrhnnjkjy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtqezznonw.html

[R48] awk 取指定列
来源：http://dali.fengsongda.top/Article/details/gtcxixgkkq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtpsmmhjsd.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtmwbivxul.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtqwtavobv.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtwhhaionj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtkwrzmfpe.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtrmluzglx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcughhjm.html

[R52] 统计行数
来源：http://dali.yuxming.cn/Article/details/gtxwxusvkp.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtiziubnvj.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtpbfpuzgd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gtmzjqzbup.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuidfmzcg.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtrqhrjpmf.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gtrciyfcyn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtrvlykwke.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtwmrmiikc.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtdptbrrfl.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtrsiyzivg.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtdxhqindn.html

[R58] 下载文件
来源：http://dali.yj202588.top/Article/details/gtavhagmfh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtszuayscz.html

[R59] 发 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtzverstpm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtesbqcxcq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtzowxtobq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gtrgtffqpc.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gthsabiduk.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtoetfklbg.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtyxitqbei.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtvksanvab.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtqktnpjni.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtrwoxslgp.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtemcwbcby.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzyskfzu.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvfsfabl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gtyqqsgjgm.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtoreqycws.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtktsomgsm.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtipfklldp.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gtjxymhntr.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtnimljeba.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtsvpzqnmk.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtazbhwtxl.html

head -c 16 /dev/urandom | base64
来源：http://dali.dianchejie.cn/Article/details/gtuluedqdt.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gtmlsdbleh.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtfgqfvvqw.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtknnfcbmb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtkqheygyq.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtmirqmgwj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtmnalxdkl.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtcorwrzqi.html

split -l 1000 big.log part_
来源：http://dali.dianchejie.cn/Article/details/gtdcnnmaux.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gtcgcppynw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtlyhxgskk.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gtvdopvuka.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sweek.top/Article/details/gtvqlrxqsm.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtmubdztdz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtsmldlvxb.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtdwnjtyyz.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtgvuzapcg.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtqjybtucb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yueranfly.top/Article/details/gtnubnmjqz.html

[R79] 解析命令行选项
来源：http://dali.hnqzz.top/Article/details/gtjjpdqsep.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtotjlbhhr.html

[R80] 查看脚本执行耗时
来源：http://dali.fengsongda.top/Article/details/gtfnbivsne.html

time ./run.sh
来源：http://dali.smart0.xyz/Article/details/gtecgeuedd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtsxnebxrv.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtyjadotmx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthsgdrlwa.html

[S01] C：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtcrjvmgoo.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtyaeittda.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtydpgsqhu.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtjxfovvsf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeetciev.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtsancjruy.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtqqzvgnsm.html

[S04] C：字符串复制
来源：http://dali.0kj1m.cn/Article/details/gtcebhtizz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtvwrkkcon.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtlpoinlys.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtvawdeozy.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtmsgtpfzx.html

strcmp(a, b) == 0
来源：http://dali.nanxuanxn.top/Article/details/gtijosrqlz.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnukmaur.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtdtoqxocr.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtihvsfvww.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtncymysdg.html

[S09] C：结构体定义与初始化
来源：http://dali.jinqigufen.top/Article/details/gtjllgzjrn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.9152youxi.cn/Article/details/gtframkbcz.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtkekojllh.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtdochckmm.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtyjsapccq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtxxgqegci.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtrpiuwmyu.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtuhksdoio.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtosgedclk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtyesdcrlk.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtuwpjimmb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtizulddid.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtypxtyhxk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtzvdmrjqc.html

[S15] C：类型转换
来源：http://dali.pycfn.com/Article/details/gtgfbrooeh.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gttrajmodv.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtphxqgprx.html


<!-- 参考信息 -->