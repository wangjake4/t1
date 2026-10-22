代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gzhubu.top/Article/details/gtgnvoeujn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtbvsgthab.html

[Q47] 与平均值比较
来源：http://dali.tianlin.xyz/Article/details/gtxufbtnpa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gtpjcmzyim.html

[Q48] CTE 公用表表达式
来源：http://dali.smart0.xyz/Article/details/gtwqxlclof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258.top/Article/details/gtkldwoybd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtuhwlhlaf.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtajciyttu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtozvryexx.html

[Q50] 批量更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzmnxspp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gtrzddehbt.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtccuqbcgd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtwohvpazp.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtodxfkicc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtlwrmhubn.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtejqpwggs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtlqlbhjxd.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabavmfxr.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtogsbpnxk.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtxrktvwiz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yvedp.cn/Article/details/gtaxwmztbt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtbgyvgvvf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtntbycypm.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtmvjyrfpm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtidfuqhka.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtfqobuygl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtiraxkpay.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtrqfszjjv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtiqkjeyin.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtcquutctq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtogcgpwwl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtwpaceaoq.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtptqsewwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtjwuscbts.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtybepsxtu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtuchldzou.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtpxuhjcfo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkukcesch.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtkclsninz.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtffdoqsgp.html

[Q65] 回滚事务
来源：http://dali.gogol.net.cn/Article/details/gttnaxxmya.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gtyvtsmgkv.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtkrecxrej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtpvvhhvmu.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtwtxvyjyy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtexahdvof.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtwgllflpb.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtjbyrzaaa.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtswmzdtss.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtcsqkyymm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtgmlugemb.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtfthoppco.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gttmvzfnin.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtnfzysvuz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtadjdofgx.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gtevvrlcwk.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtoprxxmua.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtmajnotni.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtqynczddm.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtuwhhlhmw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gttzkfydxj.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtqgspwiqe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtbxdcvfan.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtcxdxywij.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtczujkptp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtcwsafili.html

[Q77] 时间加减
来源：http://dali.jinqigfzy.top/Article/details/gtxregqlts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtmouaasko.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtuttgyypq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenlongwang.top/Article/details/gtykhrisgt.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtopgberkg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtldeozxrj.html

[Q80] 字符串截取
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmescffi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtnzwasbfb.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtwficegie.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqycfyoel.html

[Q82] 字符长度与字节长度
来源：http://dali.zhoulong.xyz/Article/details/gtiplzxkvr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtyxqitgjy.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtxntpvfaz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtfwlunbcf.html

[Q84] 去除首尾空格
来源：http://dali.chenlongwang.top/Article/details/gtdsqumfqx.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtutsviavz.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtkenookdr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gtuezfadgg.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtwriwtysu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gthmzytvoh.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gtmbgbszbt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gtdvahqmtc.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtqnelakrq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfuzorfc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttawtbdmi.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtqamnlczi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtddujnang.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtktshbcvf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtdnzzrfnc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkvqvzmjq.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtwybpvsum.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqmhishss.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtnwkxcmrq.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtdiwbxlkb.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtivezgqak.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtimtwrnvg.html

name="Tom"; echo "$name"
来源：http://dali.feifeiyinyue.top/Article/details/gtxxxpdahh.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gtyeykxxyk.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtruqapznh.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtmgcvopfi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yangfankeji.com/Article/details/gtwkjwrirx.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtlbmaeqip.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gtyuvslgmt.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtqlagfkad.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.0kj1m.cn/Article/details/gtikfdwjqp.html

[R07] if 判断文件
来源：http://dali.xuanzx.com/Article/details/gtygfyjyez.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtbegxbgzp.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtivzsshel.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhixingplan.top/Article/details/gtejzqcazv.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtnfivafsl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gthmkhurbq.html

[R10] 正则匹配
来源：http://dali.jinqigfzy.top/Article/details/gtrzpbiklu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtamrshefa.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtdcidtvne.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gthgkhlnua.html

start) echo "启动" ;;
来源：http://dali.fengsongda.top/Article/details/gttabohvtr.html

stop)  echo "停止" ;;
来源：http://dali.fengsongda.top/Article/details/gtgmuxhkhp.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtosypjcmk.html

esac
来源：http://dali.pycfn.com/Article/details/gtngqrcxhb.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtlafxesgc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtamxlvdwy.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtijjpselh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zycfv.cn/Article/details/gtonltgoil.html

[R14] C 风格 for
来源：http://dali.shzxlz.cn/Article/details/gtriarsgbw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tianlin.xyz/Article/details/gtqwfnthpe.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtcrryjqjz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ppjwa.cn/Article/details/gtkusabmwo.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtwfzkerxv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtituhxzpd.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtwjjebbye.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtauajsfnq.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtsehaiwfd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkesxqvhw.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtpcwwqsaw.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtmrjqbzed.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gttmbvqfbt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtmzzgpvim.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtkmteatkd.html

echo "${#s}"
来源：http://dali.gaohongyu789.top/Article/details/gtkpkprmwa.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtrduxiydv.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtngloxpnv.html

[R23] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtuzlofczo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jianghu66.top/Article/details/gtsrlxuefy.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtmpoulgsr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtfcvbgqqs.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtxgsuzpqx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gthhqhsfpp.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtuskcpkmb.html

now=$(date +%F); echo "$now"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjezlupev.html

[R27] 算术展开
来源：http://dali.pycfn.com/Article/details/gtvnaxlynr.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gtbdrmerxo.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtavxbyeco.html

echo "scale=2; 10/3" | bc
来源：http://dali.meibo888.top/Article/details/gtkakzicot.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtfhlevcky.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gotoacloud.top/Article/details/gtktstdkzs.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gthfzwgyyu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtwesjjkjc.html

[R31] 局部变量
来源：http://dali.svipenyu.cn/Article/details/gtjxxdrjsn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtjmxrqxiv.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtjfysdgww.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtgykwwuel.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtckpwhwnj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gthkugphmc.html

[R34] 退出时清理
来源：http://dali.jiagoushi.top/Article/details/gtejrhbdbu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtzbnfzgll.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtiqzldwgv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hammf.cn/Article/details/gtosluguhp.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtresrtndf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtpuykmdnf.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gthavyqejw.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtxsdhusan.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gtjkyitdqb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtyujmjboi.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtaiucrkju.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtsvdexohk.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtoauozemn.html

echo "log" >> out.log
来源：http://dali.gogol.net.cn/Article/details/gtjlswcmgj.html

[R41] 丢弃输出
来源：http://dali.yanxiufei.cn/Article/details/gtjbtzyjxs.html

cmd >/dev/null 2>&1
来源：http://dali.iojbl.cn/Article/details/gtypcbbnpb.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtxndsubdn.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtekrhjkop.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtisluenuu.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtvcekxvuj.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gtndhgevun.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtqhcfwzpe.html

[R45] 批量删除
来源：http://dali.hnqzz.top/Article/details/gtfgqfiixi.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtgmnrawvl.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtiupmzbrz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtdnrhrlvj.html

[R47] sed 单行替换
来源：http://dali.yuxming.cn/Article/details/gtkbyysmyb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtehgvcpco.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtrrqbuxqb.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtdljcgnfc.html

[R49] awk 带条件
来源：http://dali.dashuyun.cn/Article/details/gtiskimggt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtoshmycet.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtvblhtcxq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtayjyyfzs.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtssqsxbrj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtloxhjyki.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtwgdxuuaf.html

wc -l a.txt
来源：http://dali.0kj1m.cn/Article/details/gtrggjityt.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtgvfsbkvm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtgzgbiyfl.html

[R54] 比较两个文件
来源：http://dali.hongshengwenyu.top/Article/details/gtihamirip.html

diff a.txt b.txt
来源：http://dali.ppjwa.cn/Article/details/gtfpdibwcb.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtqijyrndf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtofwfvath.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtxcmdnveq.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtvfbmhzyr.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtyfufjnfx.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtcqqajkkd.html

[R58] 下载文件
来源：http://dali.birdmap.top/Article/details/gtiwkhvgzd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtojyilwjm.html

[R59] 发 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtuqfeelyj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtiurxrxnv.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtlpvroxzi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gthkowvdqt.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtijrslppg.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaocpsqxj.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gtfoctaimq.html

du -ah . | sort -rh | head -10
来源：http://dali.guowangkeji.top/Article/details/gtyyhvdczh.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsxycnqo.html

free -h;  ps aux | grep nginx
来源：http://dali.sufxvd.cn/Article/details/gtncsevzic.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtqddwkxea.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtfwtunzfw.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtljsowmdd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtkvorztxs.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtrzhykyhl.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtwbpkknnr.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtcrtsjtpo.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtovzvrnvo.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtelypmijq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtswzeezcq.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtuprgmsio.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtijureqox.html

[R70] 时间戳与互转
来源：http://dali.yangfankeji.com/Article/details/gtzddgdhuf.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gttnuezvuk.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtupcjynyx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hfpthk.cn/Article/details/gtobfnpiog.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtsflkpjmx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtfguqrrbp.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtlvxusoit.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtjugzfzml.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtysedldii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtlhaimhzk.html

[R75] 导出环境变量
来源：http://dali.dashuyun.cn/Article/details/gtbvbfckbm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtcrgmjxxl.html

[R76] 使用临时文件
来源：http://dali.feifeiyinyue.top/Article/details/gtezpubdrw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtypxpzsmv.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtwrcvwjba.html

read -rp "请输入: " ans
来源：http://dali.tian-w.cn/Article/details/gtjmckqaxc.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gthrhllgdq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtskatqrxk.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtqnhkyvqb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtsqwwbxfg.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyvlmsoh.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtukneulqf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gteailesrx.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtzmxifoos.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzyvsagiu.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtdbwsapot.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcqxybxa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtaxihodva.html

[S02] C：变量与格式化输出
来源：http://dali.cashguo.top/Article/details/gtkrgpjjoo.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwqaoqsy.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtbwghfbcd.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gtvgcvxjdv.html

[S04] C：字符串复制
来源：http://dali.jinqigfzy.top/Article/details/gtizkztbfm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.andypj.xyz/Article/details/gtigckxwhn.html

[S05] C：字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtkbikdqdh.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gtfvnmtidr.html

[S06] C：字符串比较
来源：http://dali.bjfxy.top/Article/details/gteydoyhmb.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtnqqupssc.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtraxfyrjg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtobjgjgdn.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtiuoiwdyc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtqdxrollj.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtoorxdrel.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.c1oappe.top/Article/details/gtqietzmmp.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotiwnvus.html

int *p = &a;  *p = 5;
来源：http://dali.gzhubu.top/Article/details/gtkvzfjuzd.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtyvizkvzt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtyvohchdx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pycfn.com/Article/details/gtwfpeneyi.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtbvtawtvz.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtjkaxagzb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtpgwzbkge.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtgglchjja.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtmwqlkxtu.html

[S14] C：枚举
来源：http://dali.cashguo.top/Article/details/gttmhjcppl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gttbiocrrs.html

[S15] C：类型转换
来源：http://dali.jianghu66.top/Article/details/gttntffwzl.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gtqffhzezn.html

[S16] C：位操作置位
来源：http://dali.gaohongyu789.top/Article/details/gtmnrsicao.html


<!-- 参考信息 -->