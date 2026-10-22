代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gtgjbpdfyk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtfrboxyub.html

[Q47] 与平均值比较
来源：http://dali.chenlongwang.top/Article/details/gtibuwkyal.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtmvkadreq.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gthizlivax.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtdxzrwrlk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtnkyfcweu.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtwffhxyio.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtcgafktjo.html

[Q50] 批量更新
来源：http://dali.jqgfzy.top/Article/details/gtsnlsqpfc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtrnrtzpwe.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gtzforfhqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cashguo.top/Article/details/gtrffkjwxr.html

[Q52] 删除指定行
来源：http://dali.yj20258.top/Article/details/gtdsqvhmmh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtnxmsohsf.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtowkeudhx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtfqjcqgid.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgjcthgk.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtkixfhonk.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheoossmk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtxbjlrbmm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtehguipzd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtswwtputg.html

[Q57] 行号
来源：http://dali.cashguo.top/Article/details/gtxiplpwcn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtvqavxsei.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtxfaadaty.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtktwkugvi.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtkcbsftgh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtweidviko.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtlfflosdd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtswcytspu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtcwiggkxp.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gtfskskuus.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtsgyfqnbj.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtreyqgyob.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gttcdnxjya.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gteohefohc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtbcvcvwnh.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gtgenxgawu.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtoifpassf.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtbdosiqes.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtaeuqcfut.html

[Q66] 行锁查询
来源：http://dali.guowangkeji.top/Article/details/gtqjncqoko.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zycfv.cn/Article/details/gtknrqtvbk.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtchncztal.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtrrfsyqvz.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtulpyzvge.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtaersjbke.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtxeahicuo.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdadsdios.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtvdqwnyxk.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gthbpfskck.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtpxlqwvnr.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtzbgmizsf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtqenixwml.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtjwqzrlnn.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtxiyuivwf.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtpqplnpks.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtqqfmliyz.html

[Q74] 强制使用索引
来源：http://dali.wangdashe.top/Article/details/gtayagdics.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtfpbrnava.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtkqkebfnw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtiqgxcphr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtcvbrrhet.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtkzgmupvt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtfgtgitvq.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtwnrcccub.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtnmedpmde.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtadxghwqg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtxrllchmb.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtluiqbiqy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yonumen.top/Article/details/gthrmhfbjk.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtnmoqqpco.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtegywsagf.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtbnhdueyv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtatnidxqi.html

[Q82] 字符长度与字节长度
来源：http://dali.xylfe.cn/Article/details/gtjkbbirof.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtokaeuzfz.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gthqadkuso.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzhekjamb.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtvjeijhzv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtdjoycxsy.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgkyreka.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtnwxfamzj.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtiuggzlhp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gthtmdkxtx.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtlcuqqesy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gttndwusvj.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtpaimtwvd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shangyingyoupin.top/Article/details/gtpqxinoqt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtoffflivf.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtdzrjzfff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gtxxvqpmqd.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtfqkvpcty.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgxepuce.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzmpbpmmt.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtijhlsajr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjkiyzbla.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtavutfpqm.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtnvbtndvp.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gtucvoqwof.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtwumvrsxu.html

name="Tom"; echo "$name"
来源：http://dali.vqdsnc.cn/Article/details/gtohaityzm.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtohicftqe.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtsgvgjehl.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjyivlya.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gtmcldbabp.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtibzyteuq.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gthhshksdf.html

[R06] 判断命令是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtgwtguelj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gthxrjbasp.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtudlkmvkd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtxgpxhpib.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtzulagfde.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdzvqmxl.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtcwemngca.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gthzorgsjf.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gthiwugmbm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtpvtkhwmt.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gtihixpopy.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtfndmuerl.html

start) echo "启动" ;;
来源：http://dali.pycfn.com/Article/details/gtjuzspecc.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtehgdutqi.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtcehjbazq.html

esac
来源：http://dali.iojbl.cn/Article/details/gtqichceux.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtaucorltd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtlywofmnx.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtpyhjtqnm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtjahopixz.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtwcjfywdz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtgjdsgqna.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtkiaccmti.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtabxjnrhr.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtoqobgzxn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtpogdnxty.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gthrslgxww.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtkzfcylwi.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtmrbkslpj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtleeoffmf.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtwpxjnrsa.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtsctwqliv.html

[R20] 关联数组（字典）
来源：http://dali.hnxiangtu.top/Article/details/gtytakokvy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hammf.cn/Article/details/gtzqatfsan.html

[R21] 字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gtepvsidtw.html

echo "${#s}"
来源：http://dali.wangdashe.top/Article/details/gthevbyvxk.html

[R22] 截取子串
来源：http://dali.cqqwz.cn/Article/details/gtospfcmub.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtxfnrtgjj.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtnlwbuywr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtxzbgsllw.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtlrfnuswc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtsojujjrw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtoeapzoxy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtcydqnwrv.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gtjjdrucyv.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gteluysrgf.html

[R27] 算术展开
来源：http://dali.ybcxt.top/Article/details/gtdpuntjxs.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtimvoxlkd.html

[R28] 浮点运算
来源：http://dali.hongshengwenyu.top/Article/details/gtodpqzoaq.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtooqwrmcr.html

[R29] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtzzrbygxb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtktlxayuc.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtskklkkhw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gthezafwuv.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtwzvfhvaz.html

f() { local x=1; echo "$x"; }
来源：http://dali.ehwqpu.com/Article/details/gtgxqymafi.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtotefrdey.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gtvzfteqjm.html

[R33] 捕获错误并提示行号
来源：http://dali.kuanghao11.cn/Article/details/gtwhyvujow.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtqsfycnmq.html

[R34] 退出时清理
来源：http://dali.hnqzz.top/Article/details/gtrqfkjyoh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiequint.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gttvbrhsna.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtkcftgsmk.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtclyeenkr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtzylqevex.html

[R37] 把输出赋给变量
来源：http://dali.yj202588.top/Article/details/gtapbzllps.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtbuclyggs.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gtnxmkdfub.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtalyoalde.html

[R39] 重定向标准输出与错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjydwctbq.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtpwwofgke.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gtnitrulqg.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtrqkjarpb.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtkqyurgeo.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtkysonkez.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtgilzqiml.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtaewdegkv.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gtjunmfxer.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtworousqr.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtrhhykwzp.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtimdbiozq.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtvaaehjvo.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtxvnkqkwq.html

[R46] 递归替换文件内容
来源：http://dali.zdqjudy.top/Article/details/gteqzhljkz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtsphleyge.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtagcmyoqv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gtsyunhned.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtvylmwzgv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtthenwffa.html

[R49] awk 带条件
来源：http://dali.birdmap.top/Article/details/gtpzbkwdmm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtutngpndj.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gthegpraxy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwnnywau.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzrhrkgf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtysgtztqs.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdibqporv.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiideaze.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtekjderyt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtaanczpzr.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtgkazmtnp.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gtlivilunj.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gthyomuzre.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gttytwjpmy.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gttmdfuxpk.html

scp file user@host:/path/
来源：http://dali.aibaodan.cn/Article/details/gtqgbsifff.html

[R57] 远程执行命令
来源：http://dali.xziqi.cn/Article/details/gtvpsxmmqe.html

ssh user@host 'uptime'
来源：http://dali.xinyue.icu/Article/details/gtcqzxnrny.html

[R58] 下载文件
来源：http://dali.sufxvd.cn/Article/details/gthxfctvai.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxinkj.top/Article/details/gtpnlixknt.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtvqhzenxn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtfoyzodml.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtfdnneoss.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtdrnhkkdf.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtspdnuvid.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gtkhquffra.html

[R62] 找最占空间的文件
来源：http://dali.0kj1m.cn/Article/details/gtkvlcpzvv.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtlijxefpj.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtzqylqzbq.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtwdqlsufg.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtgkrusoak.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sxryk.cn/Article/details/gtiluqpgki.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gttbegbqhd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.haohaochexian.top/Article/details/gtlcypgnda.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotmbjqty.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gtqinriadu.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtqcvpzvjq.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtfaupjsfc.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtlpzjorjp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtsexotsdv.html

[R69] 生成随机密码
来源：http://dali.zhongyouzk.top/Article/details/gtmrpftxng.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrngxomxj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtvppqmnge.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtleekujtk.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtmwhrwlji.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtwotegrka.html

[R72] 等待端口就绪
来源：http://dali.dashuyun.cn/Article/details/gthdjhujhf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtpudsnequ.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtzmmzgsvk.html

split -l 1000 big.log part_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffxtpjab.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtjlaoegon.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtzhtcknyj.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtwrxodeev.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtpmxssgtu.html

[R76] 使用临时文件
来源：http://dali.vqdsnc.cn/Article/details/gtnwexsmke.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtncefoeua.html

[R77] 读取用户输入
来源：http://dali.sufxvd.cn/Article/details/gtmegohakb.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtmmoiuigk.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtpatmogtm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtivbmvfep.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtxjxqalmt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtsdktcfje.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtmnqnnutx.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gtdjaickcl.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfynkcggi.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtvswyurug.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxvpcbtdh.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtnyjrshhh.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gthgvjxbxb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtndbwgigl.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtpfmpbxwa.html

int a = 10; printf("%d\n", a);
来源：http://dali.hfpthk.cn/Article/details/gtgvrfgwpc.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gttfqinuxm.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtyarixtrb.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gtmsmacxym.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.haohaochexian.top/Article/details/gtvsnzznkp.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtrkwqjamn.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtipigjheg.html

[S06] C：字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadiacwfl.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtusekypsj.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtmwbpcrli.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtcdjqvzfl.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtdzqvrdlg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtqsiyrbbe.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtefxcpcxv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtbzkayqkc.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsehxqvbu.html

int *p = &a;  *p = 5;
来源：http://dali.xziqi.cn/Article/details/gtjbayovys.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtdftqulxe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gtuzginflj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtnoqqfjhx.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtlbqdfkes.html

[S12] C：写文件
来源：http://dali.yuanzhike.top/Article/details/gtxmjntadd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppeerixv.html

[S13] C：宏定义
来源：http://dali.vqdsnc.cn/Article/details/gttwwruizm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.vqdsnc.cn/Article/details/gtufpedtos.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtqmkicici.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtzxqpivmp.html

[S15] C：类型转换
来源：http://dali.wangshuangyany.cn/Article/details/gtoufgerfv.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtkbtsubzu.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocegmvyd.html


<!-- 参考信息 -->