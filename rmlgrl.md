代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtcjxmuybu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtqlzhrscz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhroaocv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtyaneivpc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtmevhtojz.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtxzajtbew.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtxwmibqfh.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtmppxhsro.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gttkdchrkb.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtgtfmnrlf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtksvxigaa.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtwifenkri.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtopgblzzo.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtahwexlbi.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtizstruaq.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtnrvfvpdr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrxhfcns.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnfrdsjd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtpjozmool.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtsqbomkjx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiaaoavi.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtuvmjrlab.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gthtzikolt.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtgxcqruza.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtpadsvxox.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtxnxdxwhd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtefbddtqb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hammf.cn/Article/details/gtpeaejfyg.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtvoyxrlqn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenbwihwl.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtyanqtnnc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtveiejonq.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtmpcenzjw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtepkvcgot.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtbsmaylpr.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gthbhdpmxg.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtglkhcfti.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gtxzpoekft.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtyrnflvnu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtaoqszhug.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtpccdswkh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtlfeauheh.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtqlpuixrb.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyluypfld.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gtnooyvlgi.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtjnxkjgfq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtiahaubfk.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtfctkiicx.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtttlvybsz.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtodjkshzm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtqdglsibd.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtevnwxfor.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtzwroxrjl.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtmwquuhrl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtaqgkmopc.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtyvpqywrb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj20258.top/Article/details/gtibmghnxz.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtfiemnaqt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtgtauyqkh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtesiknlds.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtgtwnllvm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtfifscvks.html

[Q77] 时间加减
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenezauyh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtdemkwail.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gtnbmhtfzp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gtmchdtbiw.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtzcczfsqp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gtlynhjtvr.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtnncgzfgn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthraazufl.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtinrvwprg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aizwys.cn/Article/details/gtsewppxzs.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gttbfrpwbm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtufuoncyu.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtrwlsgcqh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtwgobqjkp.html

[Q84] 去除首尾空格
来源：http://dali.haohaochexian.top/Article/details/gtcitqeass.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtknvpdzrj.html

[Q85] 数值取整
来源：http://dali.hammf.cn/Article/details/gtpwyicufd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtczilprev.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtffsnxuxr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtwwwtmlze.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtotaeunas.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtkmylsbnv.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtdngwnbwp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gtddsukodl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtwhnjajrv.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtlhhlearj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtdqhwuqib.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtafsuxzbq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtmqdfrhni.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqiyyufsa.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtgoiixzwe.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtpmmkxanq.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtzhqmzujp.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtygvisltg.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtvqttxkeh.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtphyavmdf.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtmdkjhvwn.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtqgpwmmuh.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtwllilsmq.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtbaccxodv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtzynpuaeh.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyaawjna.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gtnvirvilr.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtcouwjtfd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yanxiufei.cn/Article/details/gtrtsvfppt.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtkhestxww.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gtbbndgigh.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtgfxqtykf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtdfbprxpj.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtfomrdqcv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtoqcevexy.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtefsjqdaq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.svipenyu.cn/Article/details/gtjfnqqakg.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtzzhbscqx.html

case "$1" in
来源：http://dali.zhixingplan.top/Article/details/gtmlildqqr.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtyfomlndi.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtrfieltel.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtxvcvnthe.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtzhrurbui.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gtkrhklnpb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuxming.cn/Article/details/gthbfbxipo.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtudhnoung.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtiutslmxb.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtheiukexw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtxoyfbatj.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gthurrqxqq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shuidangran.top/Article/details/gthgonwxeo.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtwxiwfsyh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtzvubhmzn.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gtnnykuekw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pycfn.com/Article/details/gtrovebkqy.html

[R18] 遍历数组
来源：http://dali.sxryk.cn/Article/details/gtbyudkoxw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gtsgxfgkvp.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtdfdqinsq.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtjkglchlz.html

[R20] 关联数组（字典）
来源：http://dali.hongshengwenyu.top/Article/details/gtzsbtrehd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtrylwafnr.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedaorkvg.html

echo "${#s}"
来源：http://dali.hammf.cn/Article/details/gtgzvmdfzy.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gtifqvvdrq.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtxjenywal.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtgwrgqgmj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtnzneaczz.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtjsmiuuka.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtmmptclxa.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtfackvdcn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtvbhuhdhc.html

[R26] 命令替换
来源：http://dali.xinyue.icu/Article/details/gtnnumvjuo.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gtsjatdxbd.html

[R27] 算术展开
来源：http://dali.wangdashe.top/Article/details/gtkasoxflh.html

echo $((1 + 2 * 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtjijeyjea.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtsfnmojbm.html

echo "scale=2; 10/3" | bc
来源：http://dali.feifeiyinyue.top/Article/details/gtaowgtlzb.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gteydyjqct.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zycfv.cn/Article/details/gtyqveequc.html

[R30] 函数返回状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtnvmejvhc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtlnqtwjmz.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtaevmhvhp.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtbmxrtyof.html

[R32] 参数个数校验
来源：http://dali.nanxuanxn.top/Article/details/gtpzfmnkkk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtrnzmwaol.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtkbgxglkq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtpaaevsuf.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtfwcsjhwa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtbjksagem.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsuwtmyq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtmdcojttl.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtmiqonnne.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtetxijwym.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gtkuugikeb.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtpdzixxiq.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gtzmgsvmbb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtdkkoouzh.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtziwgsuhz.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtcvjnlfwn.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtwqpjxfhp.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtyongdryc.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtgxslpjbz.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtdyjrgbbk.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gthglsxyhv.html

wc -l < a.txt
来源：http://dali.gogol.net.cn/Article/details/gtmtillycj.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtxkalwovx.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtxephzpls.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gteygeahrc.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gtyqbleluc.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtdqluskza.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcjzzolp.html

[R46] 递归替换文件内容
来源：http://dali.daxiang520.top/Article/details/gtnzugfkts.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtolowgztn.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtytenyaje.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtskjcnagp.html

[R48] awk 取指定列
来源：http://dali.smart0.xyz/Article/details/gtndqgqnky.html

awk '{print $1, $3}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtuxqqrejo.html

[R49] awk 带条件
来源：http://dali.tianlin.xyz/Article/details/gtywpwrtgc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gtlnsqspzd.html

[R50] awk 求和
来源：http://dali.xuanzx.com/Article/details/gtlwivdkxa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gthdqfdgth.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtnwsbspvr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtiduisyqq.html

[R52] 统计行数
来源：http://dali.smart0.xyz/Article/details/gtdxpbwbqh.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gtcvnxmeyi.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtwovhwkzf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yanxiufei.cn/Article/details/gtbrccsetr.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtgianuefe.html

diff a.txt b.txt
来源：http://dali.jianghu66.top/Article/details/gtlogchtgs.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqecnenyi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtgxblwfgl.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtoeimvkib.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtcczhvmvm.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtvrammnws.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtlnnktjqk.html

[R58] 下载文件
来源：http://dali.mhx1999.top/Article/details/gtyilwtzjy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnqzz.top/Article/details/gtgttgegcv.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtuvrgsezx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncdunhjn.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gttyhtsaxq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtaoyvchwl.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gtlgfdfzch.html

df -h;  du -sh *
来源：http://dali.hywenlv.cn/Article/details/gtxwnnppdm.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gthcqrsrac.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtgrmhogkr.html

[R63] 内存与进程
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfszdfyk.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtjdjabfkx.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gttetrxdoc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtkcxalwat.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtkoiqidia.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.meibo888.top/Article/details/gtxowjqoua.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtfstfatqn.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gttklvtwnk.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gttvfsiydf.html

openssl rand -hex 16
来源：http://dali.guowangkeji.top/Article/details/gtatxmqkdl.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtqfahlzit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dianchejie.cn/Article/details/gtjtzhmzgh.html

[R69] 生成随机密码
来源：http://dali.gzhubu.top/Article/details/gtxbsbfdqz.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtraoqdpor.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtlthuhrue.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258888.top/Article/details/gtbznvkwmr.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtrvhcfagc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cheryme.top/Article/details/gtbehfypqh.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtkhtxndue.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtvfgtvvdo.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtskzjxlds.html

split -l 1000 big.log part_
来源：http://dali.xuanzx.com/Article/details/gtclxabayn.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtxqvwbjtd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pycfn.com/Article/details/gtnjenccde.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtofjyysap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtqbvbhpms.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtesshgsot.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiosyyfe.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gtimojqedb.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtrkkzpyob.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gthkpalmjo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gtinlqxojw.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtpwzbqegr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aibaodan.cn/Article/details/gtisbluxfd.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtpjmotpyt.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtokdkuoyk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtszoqceld.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtbsmqkera.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtztgomkbw.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtxfugwtjb.html

#include <stdio.h>
来源：http://dali.zhiwuduotai.top/Article/details/gtkbblzzbc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtxnqhcrwu.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtzgpbcvbl.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gtdkdefxaf.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtrraumygd.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbxmbvgb.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gtudeimeev.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.316326.xyz/Article/details/gtyfhgthbh.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtdskrladf.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtqodwwlvs.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtfomzcmjn.html

strcmp(a, b) == 0
来源：http://dali.cucudq.cn/Article/details/gtbwmdyybp.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtdwtrzwfv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gthcnpiefx.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gtpkexnoij.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtijlysrki.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtafsyaarw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtvvmpmuls.html

[S10] C：指针与解引用
来源：http://dali.svipenyu.cn/Article/details/gtnmylvjcb.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtphvkfw.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtoiwibufr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtjqsodlrw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtcattrhds.html

fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtbyedckrt.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtwrdwllpt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtairdpgpi.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtmlcdmadi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtkhsvzkuf.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaewansec.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ydzc1.top/Article/details/gtnxogucjr.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtqiyibkrn.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtqouzoolk.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtqroabfco.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtjvzwvjcs.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtdrgktooc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtwndguxdq.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtsobloctb.html


<!-- 参考信息 -->