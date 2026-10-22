代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthubthfni.html

[Q50] 批量更新
来源：http://dali.yuanzhike.top/Article/details/gtlzatzxhw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtmserxzjr.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gtwygnocnj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtyigiplyg.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gttsxtdguz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gtfhimdetw.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtddtweqma.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnyuxltq.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtrgxbyclu.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtzpetftyc.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtirdpmgeh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtrexgyldv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtzoeaanae.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtmglhmnxd.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtuzvjztyq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtynnsvfel.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gtzoguosam.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtxspjpexy.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtxlirjlye.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtxrphzkhn.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gttvoveoju.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtxwvwrzyf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtpzlwrveg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtjjbhoxqd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtvkswxgsl.html

[Q62] 分组占比
来源：http://dali.andypj.xyz/Article/details/gtzdcljklj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtxhzevdko.html

[Q63] 开启事务
来源：http://dali.jinqigufen.top/Article/details/gtqhezdois.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtsmehwrmf.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gtciybdutj.html

COMMIT;
来源：http://dali.cheryme.top/Article/details/gtkpilfkas.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtpaaizxvv.html

ROLLBACK;
来源：http://dali.nanxuanxn.top/Article/details/gtomjtilfk.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtqqukrvzh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gthuqnkxgu.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtyysneprq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtpitdumqo.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtqdhmbrol.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtflswfvpl.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtpdsokeaz.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtsbhygdyf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtmmlwtkre.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtktbsfgtw.html

ANALYZE TABLE users;
来源：http://dali.9152youxi.cn/Article/details/gtlzwmavvr.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxtcpbxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiegnsnfd.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gthfjywuqv.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzbfwtlcm.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtjnvtbynk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtdlhotboi.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtgbfmthvo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gtmflakurd.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtghsuxyql.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtzaptrqec.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswzrliqr.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtvvxwyaqo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guowangkeji.top/Article/details/gtaxhdarih.html

[Q77] 时间加减
来源：http://dali.aibaodan.cn/Article/details/gtxrbivoba.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tianlin.xyz/Article/details/gtymzvdiug.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtocbsqdlc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtqfankmkd.html

[Q79] 字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtazmauihv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gtyxeimgpc.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtehwtzajn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttxtdalmk.html

[Q81] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtynkipgut.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtcueprvna.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gthbwgxbvy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdxexbow.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtgwknhean.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpkyhmhk.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gtlksbpanc.html

SELECT TRIM(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjpqxyjyq.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtoyonojqj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gtuqqonofv.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtajvpstig.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.vqdsnc.cn/Article/details/gthetbyzdw.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gtwhjghkye.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvcgdkfh.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtzonmjwdp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtpenogxwm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.redwolf501.top/Article/details/gtadgyuznu.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtkkvabnej.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtbzblkpmx.html

[Q90] 生成序号列
来源：http://dali.haohaochexian.top/Article/details/gteqdazyrn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtfngwdzpe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvfogfpvr.html

R. Bash 专题
来源：http://dali.yj202588.top/Article/details/gtushcdldh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtoltckoxc.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtkjkpkekv.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtrdanxdbt.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gticdxouit.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjuhxbme.html

name="Tom"; echo "$name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqhpmibxd.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtwzuwhfqg.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtuavwytqa.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtciswjwsa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gttbuzgomx.html

[R05] 参数默认值
来源：http://dali.jinqigufen.top/Article/details/gtaakzzgem.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtbxuewhho.html

[R06] 判断命令是否存在
来源：http://dali.zhengqikj.top/Article/details/gtxoaukiza.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtguxabews.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gtinamtzrc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cashguo.top/Article/details/gtrvduvshx.html

[R08] 数值比较
来源：http://dali.birdmap.top/Article/details/gtnkvzwnzn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtjlqncdem.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtabmhpnbw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtedsaawaq.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtlbrdphzr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtwmdgqiyu.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtvsxnbvsp.html

case "$1" in
来源：http://dali.9152youxi.cn/Article/details/gtcnwvbhpp.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtyphpcvll.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gttldwjbqm.html

*)     echo "未知命令" ;;
来源：http://dali.tian-w.cn/Article/details/gtnynjlbth.html

esac
来源：http://dali.c1oappe.top/Article/details/gtixvcanab.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtivxtnsax.html

for f in *.txt; do echo "$f"; done
来源：http://dali.andypj.xyz/Article/details/gtuwkbvhwj.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtschpkffl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtvfznjbdo.html

[R14] C 风格 for
来源：http://dali.chenjidiqi.icu/Article/details/gtjhpoerco.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtfwhyfmzm.html

[R15] while 逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtxukzroks.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gttlnnfuyb.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gttuzplzur.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtxedydmbb.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtjbdgjuzn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gttwehwddi.html

[R18] 遍历数组
来源：http://dali.yueranfly.top/Article/details/gtwlygpftm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gttlujtsnm.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtvlixeklo.html

echo "${#arr[@]}"
来源：http://dali.haohaochexian.top/Article/details/gtmgmfpmcp.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtgwybcpbb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtxsqjyrmq.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtkohtrceo.html

echo "${#s}"
来源：http://dali.yongpay.top/Article/details/gtmzoyqpsr.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gtodwbbwhg.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtlojujwia.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtmlsiyths.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtjrywnnld.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtxwqswigp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fengsongda.top/Article/details/gtkoemugek.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtufgpxrst.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtxkxjdsby.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gtfkwquzja.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gtvmdueilj.html

[R27] 算术展开
来源：http://dali.tian-w.cn/Article/details/gttulfwcjt.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtbijxtppf.html

[R28] 浮点运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxiitlub.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gttiihpsyl.html

[R29] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtlkrqrleh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gthvxxyitg.html

[R30] 函数返回状态码
来源：http://dali.aizwys.cn/Article/details/gtvsgknhzg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtdhoyfamv.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtiymwnwdf.html

f() { local x=1; echo "$x"; }
来源：http://dali.ppjwa.cn/Article/details/gtsmfcazen.html

[R32] 参数个数校验
来源：http://dali.gzhubu.top/Article/details/gtycinseun.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtxpggaesw.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtxdqzjmpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtiinixjmb.html

[R34] 退出时清理
来源：http://dali.jqgufenzy.top/Article/details/gtxwmfgnly.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtjuxvzsjp.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtuglpjnib.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtllitxbya.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtcwuqewrj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjldvllth.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtudzglbir.html

files=$(ls -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gteqziqhvq.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtxtxmaljo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtfwlmipfu.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gthhhdxpao.html

cmd > out.log 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gttugkigye.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtmsvwqvdk.html

echo "log" >> out.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtdafbdq.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtmugfxqcm.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtycjnkfht.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtrltriwbn.html

wc -l < a.txt
来源：http://dali.fzhhl.top/Article/details/gtinevnvmf.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gthymldpzw.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtbwroaomm.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtmqhszgzp.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyuyjlxw.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtonvbonfe.html

find . -name "*.tmp" -delete
来源：http://dali.tianlin.xyz/Article/details/gtnpidojzi.html

[R46] 递归替换文件内容
来源：http://dali.yanxiufei.cn/Article/details/gtuenruhdx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yanxiufei.cn/Article/details/gtlqavpzot.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtbbwsipqd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtilvkzeis.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtoxgbcukf.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtnjjeocyl.html

[R49] awk 带条件
来源：http://dali.cucudq.cn/Article/details/gthdeghpfn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gteqvrqfkp.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gtfdircwru.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtlttafuuo.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtkstmmwpv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtmyxtsrph.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtulgkphxr.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtlycfuqbc.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtuncqyhwc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtabjdwwia.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtawrqqgcm.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtrupsldke.html

[R55] 压缩与解压
来源：http://dali.xuetiantiany.cn/Article/details/gtfqeugyiw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxgscven.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtjwrtzcsy.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwwpypoe.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gthnqgpdsp.html

ssh user@host 'uptime'
来源：http://dali.hywenlv.cn/Article/details/gthnrrqgrr.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtnbsechua.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtxvzsnvkf.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtzqhdztmh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtmlyzstxg.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtvpywpjmw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtatqqdqjp.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gttorzowgf.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtymvjifjy.html

[R62] 找最占空间的文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyyrbatdd.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtrkgpdamu.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtoydrewex.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gttmsbackr.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtckksbdde.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtplheutmt.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtgkkupzdj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtbbxspjiu.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtkrumquyn.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtezrzytih.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gtepuofusc.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtlkzkhuni.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtmcvmwnlm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtsvrzrirs.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtixzzmohg.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtiocyzrdc.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gtwvseyqse.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtznewismb.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtvzjdhhfe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtqputdkxy.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtplditqgf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gtosyxarzw.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtwqjvcwfe.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtaqfyymsl.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gttryubzpb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtfbetvske.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gtxcopiawv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtutpwbskj.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtuilpwiun.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtksslvaba.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gtawpmgbyb.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtjcnielpy.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gtlbcqkglu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtyljtcahq.html

[R79] 解析命令行选项
来源：http://dali.zhixingplan.top/Article/details/gtccvjjbqr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtugyptdsb.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtxtmetaop.html

time ./run.sh
来源：http://dali.cheryme.top/Article/details/gtavnvlsnu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjiolayiz.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtwyidyunc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtguyuckno.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtnfpnguor.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtxivyxoys.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtubogepeo.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtxarjsifv.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtmepupkym.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtkcksswbk.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gturzuafvp.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtunmkjxxl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuxming.cn/Article/details/gttkstsubu.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjkbigzp.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtuvutwrqi.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtafyaabeq.html

strcmp(a, b) == 0
来源：http://dali.yj20258.top/Article/details/gtcmuwcriv.html

[S07] C：数组遍历求和
来源：http://dali.316326.xyz/Article/details/gtiecnoxbk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtvrodcdff.html

[S08] C：动态内存分配与释放
来源：http://dali.sxryk.cn/Article/details/gtxycrsysy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gtrjorvwng.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrymjkhg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtcmpgmsyi.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtnswqlptv.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtvalqrlcj.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtlguqtuha.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.quarkkingdee.top/Article/details/gteuledxxj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtekrcnpve.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwodwvaj.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtkywmkrvd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtlddhcmjr.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gtrznckwlw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuochresl.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gteilruuuu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hammf.cn/Article/details/gtsyyuedej.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfvvjzvd.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtkzepmaot.html

[S16] C：位操作置位
来源：http://dali.yj20258888.top/Article/details/gtzdaxgitd.html

x |= (1 << 3);
来源：http://dali.jqgufenzy.top/Article/details/gtmbegglwe.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gthxnfvpzw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.haohaochexian.top/Article/details/gtgphhhfjk.html

[S18] C：命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtbxpgzhbr.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtgtvdumju.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtiibtblda.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtkyhcyrqc.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtghndbgrl.html


<!-- 参考信息 -->