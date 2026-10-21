代发 wailian999

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtglbulfvi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gttehkfoyr.html

[Q43] 标量子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqponnen.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtrjcvdpnx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtvubkcyqq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.feifeiyinyue.top/Article/details/gtdgdsnyqd.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtlzqwvjek.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtamsoslnl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtgkwbpuoj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjkltqry.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjeowhjp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gthkllgjhh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtriltrrkl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtgtictegu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnxiangtu.top/Article/details/gthuhiawjb.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjumamdcv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtejvnicgh.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gtrzhjgqvn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtfidvyzqu.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtrpgplkyd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtcdhdwlvy.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gttpanswkv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtfzsbcslg.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtxejwfghv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtkvyzwohr.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtlckmkeek.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtfnahbhig.html

[Q55] 排名（并列占位）
来源：http://dali.dianchejie.cn/Article/details/gtaqnjhqnd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gticglnbwh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtycfelxbe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gthqdeevnu.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtgonwnhmy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtafftavap.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkictijvj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtksrfihgu.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtezhtlpak.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtjhngyhnr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtegjxoodn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtlpzfvlva.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtxqkqogak.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gtiubkxfwn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gttpgavtaw.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtcoxoaqxv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtkwganouu.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gtpqqigzui.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gtkczoknym.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gtwnkuauuu.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtrthqvdln.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtencqgrjk.html

ROLLBACK;
来源：http://dali.zycfv.cn/Article/details/gttvgccbug.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtblupiurv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtejqhdgwd.html

[Q67] 设置隔离级别
来源：http://dali.jqgufenzy.top/Article/details/gtkivwemlp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gthrxwfpnq.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfesnpssf.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtjvrlksbp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtnydivpvi.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkgnvdab.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gttlovhhmp.html

[Q70] 更新统计信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrvhqcnr.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtusrredzm.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gttphuzdbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gtetxhzagr.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gtyhwjcind.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtephiplzm.html

[Q73] 查看表状态
来源：http://dali.daria6918.cn/Article/details/gthfiunert.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtlguxuqlk.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtrrvdzqbt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtbyikbbtm.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtlozfkmtj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtzhpteete.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtzjqcaskp.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtdzfkupxf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtgydopmqt.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtrxcxnarr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtmyhlxqhz.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtduwjgzdh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtcxvlsdae.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtcvljgipr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj202588.top/Article/details/gtmoyuebpi.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gtmycgnkiw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtepaducry.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtasfzozbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqqfketos.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtktjiiiat.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtxyhhteuf.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtyhagoqpp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxdbjsmkb.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtucmfyyqj.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjtvmazz.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtplquycpi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gthxazamkz.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtdntwfkwf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtxlxhytmv.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjpkxskx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gtaciluihc.html

[Q88] 行转列（条件聚合）
来源：http://dali.jlsjyb.cn/Article/details/gtugaqrsxq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.meibo888.top/Article/details/gtsqrhnbkw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gthqawuxmd.html

[Q89] 判断表是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtjjmqisrf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtzlmppiay.html

[Q90] 生成序号列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybjzrfji.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gttsekcgnr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtciiogvyk.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gtjixcktno.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbtcvnaxz.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtskcgccfx.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtbwhktiyo.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtsbhjktsn.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrbwrrjd.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtciqvvizj.html

[R03] 只读变量
来源：http://dali.ppjwa.cn/Article/details/gtcofqivas.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtatzanrmd.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gtovssjfhb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtcjzvpfud.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtzexoadli.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtznqzuvni.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtclxuycnp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtbmcvfvan.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkpandjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtccsycbri.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtivokxiei.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gtyvcmmlvz.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtdrmijeue.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtkdapvgku.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtimhrnlah.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtjbxrtlup.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtpgsczigc.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtczvgizas.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtzdeesjxf.html

stop)  echo "停止" ;;
来源：http://dali.dianchejie.cn/Article/details/gtqvrzhqcn.html

*)     echo "未知命令" ;;
来源：http://dali.andypj.xyz/Article/details/gtgatwkkhi.html

esac
来源：http://dali.nanxinkj.top/Article/details/gthctuesce.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtqvcexryt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gtmtbckcfy.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtaacpnhth.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtrujtzeup.html

[R14] C 风格 for
来源：http://dali.yanxiufei.cn/Article/details/gtsoyolxdg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gtaeytcsdd.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtcmijugsk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sysykeji.top/Article/details/gtivtxtivr.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtwzxgsdlf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtjehhggre.html

[R17] 数组定义与取值
来源：http://dali.c1oappe.top/Article/details/gtusenbmdt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtgpmusoxy.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gthrlfqexi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yueranfly.top/Article/details/gtlefnajwt.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gttlddoidn.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtrfmjhohi.html

[R20] 关联数组（字典）
来源：http://dali.cqqwz.cn/Article/details/gtfummipfo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtekqfzgyp.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gtpnqqicwg.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtpydlzprp.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtcsqncarn.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gtxlatvnfu.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvpygfsn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtorjdtlms.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtbjlebqbc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtdnkoveve.html

[R25] 去后缀 / 去前缀
来源：http://dali.hysaishi.cn/Article/details/gtqvlaqweh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtohbzqxjh.html

[R26] 命令替换
来源：http://dali.jyoumei.cn/Article/details/gtybimfovt.html

now=$(date +%F); echo "$now"
来源：http://dali.ivvv.top/Article/details/gtgwnqqbpe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gtpsgpbshl.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtuagrafsa.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gtarppkrun.html

echo "scale=2; 10/3" | bc
来源：http://dali.jqgfzy.top/Article/details/gtnrvzncez.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gthkvpfafh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tanke756.top/Article/details/gthxkzejjt.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtvotvdgke.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gtnnmmbbzj.html

[R31] 局部变量
来源：http://dali.tian-w.cn/Article/details/gthizydbng.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gthktfibdb.html

[R32] 参数个数校验
来源：http://dali.pycfn.com/Article/details/gtqvvlslzq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtngpcrjsc.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gttxvfvbiy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaioqjumm.html

[R34] 退出时清理
来源：http://dali.shzxlz.cn/Article/details/gthznkawsa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gthukqsgxc.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtegxiseaj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtiwfsykgq.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtndndbyjg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jianghu66.top/Article/details/gtzfgphzev.html

[R37] 把输出赋给变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfokekkd.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtyzvwnzuj.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gttjtsgdmm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtujdfudor.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtggrmuofl.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtpkmramcp.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gtdtizeaja.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtwnmougiv.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtbrqnlcux.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtyrflhpzw.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtfeecixbm.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtgjuwqnqu.html

[R43] 按名字查找文件
来源：http://dali.yj202588.top/Article/details/gtthdtknbo.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtrcgucopc.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtmrpzuhbd.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtlwqxignu.html

[R45] 批量删除
来源：http://dali.jiagoushi.top/Article/details/gtaiaplmjr.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtoqhdermc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gtjgpnvchs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gtdlqhzlll.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtixrhdbfa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gtjxucqipf.html

[R48] awk 取指定列
来源：http://dali.birdmap.top/Article/details/gtfgqvzikl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtxuwhjvsw.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtilomxpab.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.snrcjt.cn/Article/details/gtragziooi.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtrsggwvyf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqkjttys.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gttlvceyet.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtvsgysxqx.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtowerofzg.html

wc -l a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvvjbyoe.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtefyqgyoc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtsuljaeif.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtxfspxldj.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtjjegkctk.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtojwcegmf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtfsfcqpow.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gtknpkcjwb.html

scp file user@host:/path/
来源：http://dali.xziqi.cn/Article/details/gtszonzboe.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gtjvhddlrn.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtbadvhmhh.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtdljvyfxm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jyoumei.cn/Article/details/gtnfdkrhrc.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtfwxgzzye.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.mhx1999.top/Article/details/gtmenjjqcl.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtseufrvzm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gtlrotpsig.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gtytlfbytp.html

df -h;  du -sh *
来源：http://dali.9152youxi.cn/Article/details/gtwupalhsk.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtqpwxsaco.html

du -ah . | sort -rh | head -10
来源：http://dali.daxiang520.top/Article/details/gtqftmivna.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtecyxccay.html

free -h;  ps aux | grep nginx
来源：http://dali.jlsjyb.cn/Article/details/gtbfytodnu.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtgwwewpcs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtbicyzmea.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtyaktradi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtvxugvrol.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gtywlpmmuq.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtonrgzewn.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtwdxqywtl.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gtqwkwqptw.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtxbypmkkb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiqrixyc.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtizcenkkq.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtjffsrfav.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtpbvqzitw.html

date +%s;  date -d @1700000000
来源：http://dali.yj202588.top/Article/details/gtdbxcnfme.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtjtiaaise.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtnhsfescr.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtsppveyrd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fzhhl.top/Article/details/gthbqjimkh.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtuwyrnjeb.html

split -l 1000 big.log part_
来源：http://dali.tianlin.xyz/Article/details/gtuzpsailr.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtubkbzrvr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gtgqhvelmc.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtettvhrfm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtemttfdiu.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gtbirdpjib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtlarztskz.html

[R77] 读取用户输入
来源：http://dali.birdmap.top/Article/details/gtoxjtvber.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtsmluxgaa.html

[R78] 交互式菜单
来源：http://dali.meibo888.top/Article/details/gtmwlwmuye.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gttkkhiqgh.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtjleijrfh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtggcqmoce.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtknyqmqqm.html

time ./run.sh
来源：http://dali.sxryk.cn/Article/details/gtlbctgyic.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtkmaxanic.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtekooiddm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtytahcwqw.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtobifixzg.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtknnnsohn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuffiknwl.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtlaaxpkfg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258.top/Article/details/gtsopfgteq.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtotcrbskh.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtqpnutnqy.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtrifnotxv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtkflrlmzy.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtknnevyrq.html

strlen(s)
来源：http://dali.ehwqpu.com/Article/details/gtnxhgiwjg.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtjzgovwkr.html

strcmp(a, b) == 0
来源：http://dali.316326.xyz/Article/details/gtyvxjzjcz.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtkmpptdxl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtpqyjfxka.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gtcgtxtnmr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtmezhhzuz.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtjqhndqut.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jiagoushi.top/Article/details/gtnyqnykdy.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gtbeavjytn.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtpnbicnne.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtqcupwtme.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtrczlzkcc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifzvsgjb.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzrrsfnq.html

[S12] C：写文件
来源：http://dali.yj20258.top/Article/details/gtdvftkkra.html


<!-- 参考信息 -->