代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtmvqtgaiu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtjptryceq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtvdvawuiy.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtscooxgaa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtzxgbhnpb.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gtklynojxg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjwrschr.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtyqssamwh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gttmcrldci.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtzinwvcbw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtsmgcgzvn.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtrqoivwre.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtvopprhbw.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gtnlhitvov.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtusvjzbcw.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchfejbdt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtynfhayqg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pengpengdd.cyou/Article/details/gtqobvgcrh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtmrztleri.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkxxefjg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtoahmzugo.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtlviwgkte.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtfyyxymhc.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtavbhgsij.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtwthzplco.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gthmuyiayg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtcmojfxfd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtxgxncjcm.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtnljxnuyf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtkjopmlzq.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpzdbjyr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtsjcdwres.html

[Q63] 开启事务
来源：http://dali.dianchejie.cn/Article/details/gtgboifncy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtcfkvkghm.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gtiabubjxg.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gthrtziagb.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtqruqbjof.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexowjczq.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtxjuazlwd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtgzrpuged.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtavtmjkcn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtpbjuqhot.html

[Q68] 保存点
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbynowkq.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapcgotaa.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhddqpjf.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtcodnucjx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gtxaftrspg.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtgqgsomlx.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtaasrmtcs.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtnjyzhzvs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gtpbyqvzeu.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gtzkbaldsi.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtphmnagbn.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtyijknlqi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjsxojbm.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtcjscmzeo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtcdvjsgqd.html

[Q75] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtbfkmqywe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtovhxouor.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtljplqmxq.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzajnehn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtygdwyzbd.html

[Q77] 时间加减
来源：http://dali.ydzc1.top/Article/details/gtlyujwyrt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gticjoewoh.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtqrkgmykj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gtcvqvrpeu.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtjwinsmos.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gtdruygrki.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gtnxkgracf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gthwzrjpvc.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczlcriog.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtglqxicrh.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtjwcblqgo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtgepqvqlz.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtlamphmwe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtpndcpdmh.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtwrghguaq.html

SELECT TRIM(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtxodbgjec.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnaunfvv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gteafoqtrd.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtjwkxjydz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtmzthugfw.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtwbhgrgmz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigufen.top/Article/details/gtuvdeeipi.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtbkjjcoiv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtfurzhjol.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtlnjhruqb.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtevakzxuc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtfpiqmezh.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtbuucpsnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtksxzpdaq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtmczdckcg.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gtlsiidani.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsketsmeb.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtmkkljfsa.html

#!/usr/bin/env bash
来源：http://dali.hysaishi.cn/Article/details/gtjyhdvwkn.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtmikfjexj.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtevhglclo.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtdgngdafj.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gtdzzykyge.html

readonly PI=3.14
来源：http://dali.shangyingyoupin.top/Article/details/gtpdenieos.html

[R04] 位置参数
来源：http://dali.nanxuanxn.top/Article/details/gtpmpmtgbg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtjgfeeaha.html

[R05] 参数默认值
来源：http://dali.jianghu66.top/Article/details/gtrrdjobck.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtlbklwutv.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtanyflplq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbipnujpw.html

[R07] if 判断文件
来源：http://dali.ydzc1.top/Article/details/gtozlfohzr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gtoderfawc.html

[R08] 数值比较
来源：http://dali.guannengcc.top/Article/details/gtrwuourjq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtxqhvrcel.html

[R09] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gttlkrtktr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gttqqaprwh.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gthwfzfljf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xziqi.cn/Article/details/gtmmtgburs.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gtbarrhczb.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gtwmkzbnuz.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtxlghgvxn.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtfvoiokue.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtlfqubfwa.html

esac
来源：http://dali.316326.xyz/Article/details/gtkxzcscji.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtdziukhwc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtpdkldgyb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtdwzzghqw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtafgucgsl.html

[R14] C 风格 for
来源：http://dali.xuanzx.com/Article/details/gtoomvtqmr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtoakitycq.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtqpumhmwc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtqjhnhmce.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtkuwcjahs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtegskovhi.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwwqevim.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hfpthk.cn/Article/details/gthmrkuzua.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtwwhpyerk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gtugdiqtwz.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtsrusvesq.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtxzgomxsh.html

[R20] 关联数组（字典）
来源：http://dali.chenlongwang.top/Article/details/gtvnnejmxj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtyfwapipt.html

[R21] 字符串长度
来源：http://dali.bjfxy.top/Article/details/gtsuwdcsfu.html

echo "${#s}"
来源：http://dali.yuxming.cn/Article/details/gthkgbykkd.html

[R22] 截取子串
来源：http://dali.dashuyun.cn/Article/details/gthkwmheaf.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtsivqfnvw.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtffvurgol.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtugxwnnpd.html

[R24] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtaxxslxqm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hysaishi.cn/Article/details/gtpovytwzr.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtwccmfoge.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgfzy.top/Article/details/gtzslnohnu.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhethhcl.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtsyyphgzo.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtgwzxpimk.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gticbyrdku.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gtczymffab.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtbgqyegte.html

[R29] 定义函数
来源：http://dali.yongpay.top/Article/details/gtgexeybeh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shangyingyoupin.top/Article/details/gtmtisfsiq.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gtqgupklze.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtxtscnasl.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtcxhgqpau.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnqzz.top/Article/details/gtircwofdv.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtsvfbuyfu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtlrxwpvvl.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtpyriicyc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigufen.top/Article/details/gtoqoaqipp.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfkpktcv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtbrtdgzjn.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtrrcyskzv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtnfligrjt.html

[R36] 并发执行多个任务
来源：http://dali.yj20258888.top/Article/details/gtzvwdmjws.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtyokfihqn.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gthjpjwhrt.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtewyphkyr.html

[R38] 管道串联
来源：http://dali.ybcxt.top/Article/details/gtpglxvviy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gtquhvzknu.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtikdteofo.html

cmd > out.log 2>&1
来源：http://dali.sufxvd.cn/Article/details/gtayxhcaqo.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtnyfyneoi.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtyhvudqsn.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtdfpcuqrl.html

cmd >/dev/null 2>&1
来源：http://dali.yonumen.top/Article/details/gtswcshfbw.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gtzkxhdcgw.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gttjoadmbg.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtayfioviq.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtoejwylum.html

[R44] 按修改时间查找
来源：http://dali.daria6918.cn/Article/details/gtcixkxsiv.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gtehdilebv.html

[R45] 批量删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqfxxoze.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtulgzuxwi.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtypozwtdw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtqsfqcxdf.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gtiazlnimr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ybcxt.top/Article/details/gtxgybzshu.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtyyqtscuk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqvmmgsb.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtpqexyjvv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jyoumei.cn/Article/details/gtvkvakpxe.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtmsfqturn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtuivuepms.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gtbbgtdzbe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gthcctpzku.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtdbqtuxaa.html

wc -l a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtgipomefq.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtpbophxhk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gtzhkxvrpv.html

[R54] 比较两个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqusrfig.html

diff a.txt b.txt
来源：http://dali.yj202588.top/Article/details/gtuuhowfvx.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtwhjmomgk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtbsylwdye.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gttgcanjum.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtsyyiyzkx.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtvdfmpglo.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gtwrluuosk.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtauxugjfe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdxpqxir.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtkuneteby.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtdoyihdru.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtlinnzoxp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtlycdlujo.html

[R61] 磁盘占用
来源：http://dali.shangyingyoupin.top/Article/details/gtdjbwminf.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtwdthxpvk.html

[R62] 找最占空间的文件
来源：http://dali.wangdashe.top/Article/details/gtkzwiihax.html

du -ah . | sort -rh | head -10
来源：http://dali.pycfn.com/Article/details/gtsckgrief.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtmuxmumky.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtkkcxqgxv.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtmcncddwj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtykhualmu.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gtwqbomikz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gthsgumzvj.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtzplbgcph.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtjqammrxr.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gtqxyezeax.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtnkhqqmea.html

[R68] 计算文件校验值
来源：http://dali.shuidangran.top/Article/details/gtvwurbmco.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gtzafenfca.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtsnmctcgs.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gtacthagph.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gtzoaszozb.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gtyoxelpyd.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtagdejzpl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtiptgquqw.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtezxvgcja.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtqsqbbovl.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtlvzcyynz.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtcssgyhry.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtazpfqtji.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.vqdsnc.cn/Article/details/gtttoleluq.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtixgqmwfc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gtjiyhyobm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtpkhferov.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtlmixiuym.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gttdvqcfzw.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtjemljeha.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtanlbjlxx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtxtkpawuw.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtkckshasv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtkzqmvadg.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtcqvzscnu.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtlzabcndq.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsncgdabq.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gtcidsgrvi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnuqousrv.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtvjreximd.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gtkbomnxlr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hysaishi.cn/Article/details/gtauxdunmm.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtaclyddzd.html

int a = 10; printf("%d\n", a);
来源：http://dali.pycfn.com/Article/details/gtealtmhoq.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtqnthkflr.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gtceyeogkm.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtqfojqxfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gtudcucbeg.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtcjsguwwe.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtrhfkhvrx.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtlrkflria.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtrinuuzka.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtcqhzzpxu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gtnexhftis.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gtceulzwjw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtymtgacrb.html

[S09] C：结构体定义与初始化
来源：http://dali.shuidangran.top/Article/details/gtrkjfrxdi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtcodkhnpv.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtftpxdzas.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gttxlrudps.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtfbjvuyhy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtdknmbjgn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dashuyun.cn/Article/details/gtsktmfebb.html

fclose(f);
来源：http://dali.yuxming.cn/Article/details/gtdiurzfmp.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtprhccaen.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtqwfjnmxc.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtpcebcbfz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtvclqjmgx.html

[S14] C：枚举
来源：http://dali.fzhhl.top/Article/details/gtxukqaelx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nwbrower.top/Article/details/gtwikkyxim.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtkkrrzacn.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtmhhtlgyl.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtukoovgsp.html

x |= (1 << 3);
来源：http://dali.fengsongda.top/Article/details/gtfzzhjbvr.html

[S17] C：安全拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtdvwftetl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gtjmybmqpk.html

[S18] C：命令行参数
来源：http://dali.yj202588.top/Article/details/gtxlhzdndy.html


<!-- 参考信息 -->