代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gthikurmog.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtacjpknta.html

[Q47] 与平均值比较
来源：http://dali.gogol.net.cn/Article/details/gtpicnybie.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtbgkuudez.html

[Q48] CTE 公用表表达式
来源：http://dali.zhengqikj.top/Article/details/gtkgdlhwfy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtrwcbmdrx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtplpiiqsb.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtzbjsnxjb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gttgzcwnly.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtiqieyaco.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yongpay.top/Article/details/gttikrcqev.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtrohsvfjv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gttcmeylzg.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtvfqctbkw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtvjjqoyhj.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtuukbwsgu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtxqymihox.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtatfhzpby.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtdnataazm.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtzfdsbyyt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtgazyrbyr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtdfozygdj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtmrysephx.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtsqygfbdl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtaixpotxg.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtxwxmpbzf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtapilgigr.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtutsmfpjh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtanmyczop.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuzjrpsu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gtrugpyumk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtprdcdcsh.html

[Q61] 移动平均
来源：http://dali.xziqi.cn/Article/details/gtnlmrkguu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtngjdtzjk.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtnyofwcqu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtrycgyhjv.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtefcsvnsy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fzhhl.top/Article/details/gtnmoquvda.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtjpgypwdo.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtkaaplsco.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gtkujocqfl.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtuwsrevxh.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtzzngtoxb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtkfjhatqf.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtwojboubl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtzjvtsaqo.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtmrmgdqdy.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gtxcubarek.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtsysqzpgd.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gtvwhmqhjd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtodczjkdc.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtaakulvjv.html

ANALYZE TABLE users;
来源：http://dali.jinghuilouyu.cn/Article/details/gteekhxecm.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtnlbkbxya.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtwcujhdrf.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtqqfxlbsy.html

SHOW INDEX FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtyqvvmbyf.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtqpdeebac.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.meibo888.top/Article/details/gtkcvkyufb.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtjnciljsw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtzegojjit.html

[Q75] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtxicemgqg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pycfn.com/Article/details/gtgohxocqo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtjwotwwbs.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtddislsqh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jianghu66.top/Article/details/gteewtxptp.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtatsvnomo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gttrcxhpsq.html

[Q78] 当前时间
来源：http://dali.yongpay.top/Article/details/gtpkpciein.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtnvsnpuxc.html

[Q79] 字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyggxnihw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqkaixov.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtegvzygmq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gteednwjcx.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtnxniugay.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtqhcmkgzb.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtvphkqhfd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvwyzzqta.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtpmgbvcuh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtazexwduy.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtbctaokma.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtnkokland.html

[Q85] 数值取整
来源：http://dali.guannengcc.top/Article/details/gtkuulczlc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtaqthjkci.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtnzwojwyz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtmdvxyrvu.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtymohiywj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtinrzbwvz.html

[Q88] 行转列（条件聚合）
来源：http://dali.316326.xyz/Article/details/gtxjnbwqgp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuanzhike.top/Article/details/gtzpqwaerz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtdtorkges.html

[Q89] 判断表是否存在
来源：http://dali.ybcxt.top/Article/details/gtdsjakwaw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtrmdjpmll.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtuzhczete.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtdvypjlhv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqhlbknkg.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtyswfbkji.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtanhhwsqn.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtfhjnfyqm.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtduqdrxqr.html

set -euo pipefail
来源：http://dali.dashuyun.cn/Article/details/gtfwtwvcve.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtxgrhkzcz.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtjhhlebrb.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtgtpwbzgq.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gtcfxyovme.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gttxunlzmi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gtfeihafyu.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtxlhtgxbb.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gtpiugkkye.html

[R06] 判断命令是否存在
来源：http://dali.gotoacloud.top/Article/details/gtyouriggl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtchjbdjfv.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtofzdljxw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zycfv.cn/Article/details/gtunulshta.html

[R08] 数值比较
来源：http://dali.yonumen.top/Article/details/gtjsdmvtyj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtziszxxsj.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtwppbuywm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gtubfhbvgw.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gttfghggli.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtlutxsbws.html

[R11] case 多分支
来源：http://dali.316326.xyz/Article/details/gtfspuwcxm.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtxayysetf.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtoyqpprjs.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtqmrgvjie.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gtwnyrggbe.html

esac
来源：http://dali.ybcxt.top/Article/details/gtgsgxjcsk.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtbutdktqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.iojbl.cn/Article/details/gtxalpwkdu.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtmsciwotz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtymebwmmf.html

[R14] C 风格 for
来源：http://dali.zycfv.cn/Article/details/gtayxapzga.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtmzeegqpt.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtynvuqkiq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtmtfygvti.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifcugprx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtqcrrnqgs.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtzcftbwap.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gttsdtggfz.html

[R18] 遍历数组
来源：http://dali.jqgfzy.top/Article/details/gtdopapecr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtavplyduc.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmmgksne.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtqeiqrhaz.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtiygayyxp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gtkfxxyiin.html

[R21] 字符串长度
来源：http://dali.chenzaomai.com/Article/details/gtidlxtazl.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtlsnykcph.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtyngykcty.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtrdybldpv.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtnpkenren.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtgjvxsrko.html

[R24] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtdnoiuowc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtkodmntab.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtonrxvnri.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.feifeiyinyue.top/Article/details/gtlxvbpser.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtlzlppimy.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiymvxiyq.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtfgfhsigh.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtwuoijqwk.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtjburzveh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gthotinxvw.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gthzzmobpb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtrdllbras.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtfboqrjkn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtiypaqfpv.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtoztgamrq.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtmdwogndr.html

[R32] 参数个数校验
来源：http://dali.ydzc1.top/Article/details/gtuczbjjen.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtghidiusy.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gtmiobgngo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zdqjudy.top/Article/details/gtadlowbcd.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtloccuhrv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegaqvnom.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtstxkytup.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtztxnfqdo.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtepoxylfb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gtvimqbnsk.html

[R37] 把输出赋给变量
来源：http://dali.zhoulong.xyz/Article/details/gtswihhoct.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtjgdoscch.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtztakofah.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunqnrnfs.html

[R39] 重定向标准输出与错误
来源：http://dali.chenzaomai.com/Article/details/gtlcnkzvac.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtrywcfbsf.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtqpcwedza.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtrlzmdhaf.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtockynmxs.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtzxguxjxe.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtqauiiken.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtataeowio.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtzjhqiumm.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtcirlzhwy.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gtdemymtyu.html

find . -mtime -7 -type f
来源：http://dali.cqqwz.cn/Article/details/gtfuhsdeht.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtezbhhsaf.html

find . -name "*.tmp" -delete
来源：http://dali.zhengqikj.top/Article/details/gtkfctypqs.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gtpxejwsyv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhongyouzk.top/Article/details/gtartxuxkk.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtctdvjckv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jyoumei.cn/Article/details/gtklzikbxp.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtkmnraayd.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtiqgnlwvs.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtkeczgrgp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtfdanuhyq.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtcktigcmy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtavxzpddd.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtdrdkehut.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gtpekevhfs.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwefwmyk.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gttltbrpzr.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtahdppbyz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtblylpfki.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtmkheihoo.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gttjxmwero.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtmtkffbms.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtoaxbmtad.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtvhoxohka.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gtfypequge.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtkckrwpzw.html

ssh user@host 'uptime'
来源：http://dali.zhiwuduotai.top/Article/details/gtqwynoera.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtqmqtimvp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gttwffcfoo.html

[R59] 发 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtsfsvgoum.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtufygriql.html

[R60] 只看 HTTP 状态码
来源：http://dali.snrcjt.cn/Article/details/gthxybqdvn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gtvpdbjvzq.html

[R61] 磁盘占用
来源：http://dali.chenjidiqi.icu/Article/details/gtqlwpkmiw.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gtdegpnmfd.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtlidkblwm.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtqtwcsmiz.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtvstxxhql.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtomgbrvvs.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtmscmqibm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtrpnqdfij.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gtgmrsnyou.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gthywwoqhm.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtjfvcgrlm.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtmoxihfiq.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gtewwfarhb.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtrufrpqwh.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtjmhisenv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtfdokxbdt.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtmechfsok.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtgtsprxkd.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmvusimi.html

date +%s;  date -d @1700000000
来源：http://dali.yangfankeji.com/Article/details/gtuwyfszwg.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtxdyjzyec.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtpeqwwzgn.html

[R72] 等待端口就绪
来源：http://dali.vqdsnc.cn/Article/details/gtmbzuzmyd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sysykeji.top/Article/details/gtpjhcdgtq.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtzxxcdibx.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwiigqjh.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtmnwbcbim.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtuerdqoef.html

[R75] 导出环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtcprlzwyj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtdgyoyiqk.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtbmcmjlpt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gthxjkkvgr.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtjvnqxjgj.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gthyqygoff.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtfsqrncsc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtjbejbqbl.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtzfnakopj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtlonhwysf.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtiwpwbqag.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtdwuiyizy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtejxpzfhf.html

S. C / C++ 专题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoumajmyl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnaanwrac.html

[S01] C：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtqfmjltkz.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gteevhmcmb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtrgdymsbx.html

[S02] C：变量与格式化输出
来源：http://dali.zhixingplan.top/Article/details/gtshfomkzv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jyoumei.cn/Article/details/gtductxycj.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtbstusheg.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtyuywfoni.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtntruyzyu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtsqqidshs.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtqapkbemc.html

strlen(s)
来源：http://dali.yj20258.top/Article/details/gtlrpxzrps.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtrdarzfrr.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtcggmztbx.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtiiiyywcc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pengpengdd.cyou/Article/details/gtihctaogw.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtfgcmkeop.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gthxarychm.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtvniguthc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtiphzopgs.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtmjoxbpfu.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtkxmamenu.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtmzanbgio.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtoucifyoe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtlyhfsrtk.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtuxyxxdne.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtqgikanhg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtxfnmofcf.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gtjpgatbbx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtpuxhktca.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtbptsbldb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefzyalmg.html

[S15] C：类型转换
来源：http://dali.jinqigfzy.top/Article/details/gtjccutgep.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpntsvwc.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtmxuuhiri.html


<!-- 参考信息 -->