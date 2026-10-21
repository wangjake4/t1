代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtimxiqxbn.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gtozxcmtoo.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtfrnvkkki.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtgsvftznm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtdvpmkipm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtaonjwygd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtjveiifni.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtgxgmkmdc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtlmtahgxk.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitgthytd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtdbqwtrys.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtgmsqzwfg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtfmrsikan.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gthkyagnwz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtrmmiiyxs.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtgnmatqkx.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtjnqbxugj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtgwhofzko.html

[Q62] 分组占比
来源：http://dali.fzhhl.top/Article/details/gttysgtpqx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtsppatbzk.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtmtpdusmi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtdgqomede.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtziwjlrad.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtwxudyswl.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtowyvotga.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtfdzvbdij.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtefrlhvpp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtenoemxic.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtaoytcbes.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gtlrxrzpvv.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gtjmkjtgsb.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gtaegkaztl.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtmhcolzck.html

[Q69] 查看执行计划
来源：http://dali.dashuyun.cn/Article/details/gtuugtnade.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtehhzwnrt.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtwauigexo.html

ANALYZE TABLE users;
来源：http://dali.xuanzx.com/Article/details/gtvynwihby.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gtjpvenkvf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nwbrower.top/Article/details/gtmnszyqbr.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtzofzlyuv.html

SHOW INDEX FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtclnmavmw.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gthyitlrgr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtxqrqerux.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gttmblwywm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtsxjqdlsc.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtvmnglrvf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtunncrilf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtxytwjmwx.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtqhnsiqtk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gtarcldchb.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gtjmoktdlr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtrhfakjgd.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gtoleddwtk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtwclnleir.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtdiirhett.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gtrrurlprg.html

[Q80] 字符串截取
来源：http://dali.jinghuilouyu.cn/Article/details/gtsigcnlxv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtrpwopiom.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtmmjuoawu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gthhmhdxon.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtkazqlkpk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtdbjcpqol.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtnmnvjdzc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtyxmzijgv.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtduqurebn.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gthwhktjqd.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtwzbycuad.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shzxlz.cn/Article/details/gthxkeogsf.html

[Q86] 读取 JSON 字段
来源：http://dali.daxiang520.top/Article/details/gtxsdaugjj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtiofzvekp.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtcamrdyhg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtlhcltcli.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtmgjkhdkc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtxdtivizd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtfluvaekw.html

[Q89] 判断表是否存在
来源：http://dali.yuanzhike.top/Article/details/gthricejjn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtwdydjlss.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtobirugrr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtqghyfawt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxuqlcnxq.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtelomxslm.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtckfavuhr.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gttottbwzi.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtmzootdcr.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtmilfrbtd.html

[R02] 变量赋值与使用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamnpgjgc.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtokhhowwr.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtcgwiplag.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtfdrpumtp.html

[R04] 位置参数
来源：http://dali.jianghu66.top/Article/details/gtwejjoonl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtfvafupgw.html

[R05] 参数默认值
来源：http://dali.aibaodan.cn/Article/details/gtnwoztgpv.html

name="${1:-default}"
来源：http://dali.daxiang520.top/Article/details/gtwzmmpkhk.html

[R06] 判断命令是否存在
来源：http://dali.jianghu66.top/Article/details/gtmfgbnyyt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtqathjikw.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gticnpneyg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gtatlwpsqr.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtuekkcjdo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtltvigniu.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtmvrdesss.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtzcjugfoq.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtlhpmuyjd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuckhthz.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtpoeesbmt.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhzzhgix.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtgmwvjylo.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gtwjojkcep.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtnuovlayv.html

esac
来源：http://dali.hammf.cn/Article/details/gtbbgwstsp.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtdncbhrwl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtxlrxejtl.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtgmrniueh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtmnliftgw.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gthqgttcrn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmalxijt.html

[R15] while 逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtnddgeoum.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aibaodan.cn/Article/details/gtzoxfhzlj.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gtogvqpxvi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtimrjwrzs.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtymtahqob.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gteghpsbbw.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtepzgwueq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtwwbixdwt.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtbbmsudav.html

echo "${#arr[@]}"
来源：http://dali.mhx1999.top/Article/details/gtywldnnfw.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtvpeuhlqr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtmqnfqmbp.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtszyndcoj.html

echo "${#s}"
来源：http://dali.cdnleiting.top/Article/details/gtgfriqvmy.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtrapagktg.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gthhxmgtba.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtocgcvxwa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.snrcjt.cn/Article/details/gtrzskjajq.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtxkjqoisn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtmtuzihdo.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gttzpdnegd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtakjnkbkw.html

[R26] 命令替换
来源：http://dali.cashguo.top/Article/details/gtisathcvn.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtxymuzfya.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gthznohtbt.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gtumxqjpmh.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtioavbayp.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtsxkxhikv.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtitrehitr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtqeohxkoa.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtrjnohbhk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nwbrower.top/Article/details/gtuhluadvl.html

[R31] 局部变量
来源：http://dali.quarkkingdee.top/Article/details/gtrzosiqwc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtnvnudhsj.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtujheyyry.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtygtajmwr.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrshiznjf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqglnehl.html

[R34] 退出时清理
来源：http://dali.guowangkeji.top/Article/details/gthybiwkvm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtdwjnlnjc.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtfqndezji.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtrdnckmtt.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvasnblgw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtkpkgbnmg.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtlralnkax.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtzenwfpuq.html

[R38] 管道串联
来源：http://dali.redwolf501.top/Article/details/gtsjafgmqi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nanxinkj.top/Article/details/gtivasgwev.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtjfogwjso.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gthzrkmhrm.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtitgujnxb.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtgarybtnf.html

[R41] 丢弃输出
来源：http://dali.hfpthk.cn/Article/details/gtzckjqbxk.html

cmd >/dev/null 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtzerbyxkg.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gteoauhlsf.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtgudolijc.html

[R43] 按名字查找文件
来源：http://dali.daxiang520.top/Article/details/gthfqtwulo.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gttyfjhcgy.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtozaczfwi.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtgobcomen.html

[R45] 批量删除
来源：http://dali.sxryk.cn/Article/details/gtuebqsraf.html

find . -name "*.tmp" -delete
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqjfyjcf.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtyphrcvgd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtngldxprc.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtklmhotif.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtzdndtlsu.html

[R48] awk 取指定列
来源：http://dali.0kj1m.cn/Article/details/gttgajstyu.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtsprwvkri.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtcgjpcsoj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtdujqmshu.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gtytematmu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtjllkeebo.html

[R51] 排序去重取前几
来源：http://dali.xuanzx.com/Article/details/gtxugmifrw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtqwhnbidw.html

[R52] 统计行数
来源：http://dali.jinqigufen.top/Article/details/gtpebxnhfj.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtswolpmtn.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtbgdlmzft.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.nanxinkj.top/Article/details/gtldkaskyp.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtznwavaid.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gtnnfcsnbi.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gtrxhthpvm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtgpzifxfm.html

[R56] 远程拷贝
来源：http://dali.aibaodan.cn/Article/details/gtqllbnrzb.html

scp file user@host:/path/
来源：http://dali.c1oappe.top/Article/details/gtnuevhjya.html

[R57] 远程执行命令
来源：http://dali.cdnleiting.top/Article/details/gtriuwyvdv.html

ssh user@host 'uptime'
来源：http://dali.cashguo.top/Article/details/gtlokxygmj.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtxecnefte.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtwqxluuai.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtcngbqver.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jqgfzy.top/Article/details/gtlbzwmxcb.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtjdksycem.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtvvemnfmw.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtmhakyxth.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkarvthi.html

[R62] 找最占空间的文件
来源：http://dali.jqgfzy.top/Article/details/gtmjdzkmod.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gtplgiftfe.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtkkolpztg.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtngkyeoex.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtnjeizhsn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtvkomewzx.html

[R65] 查看端口占用
来源：http://dali.snrcjt.cn/Article/details/gtdibbqidr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtzcisleib.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtqbxzasev.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtvmtercmw.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtyunroecy.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtbudeuifh.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gtxgnnlpll.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtvhykooft.html

[R69] 生成随机密码
来源：http://dali.daria6918.cn/Article/details/gtxhjihjlv.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gteapquxbb.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtanjegmkx.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtizbkxhmq.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtnsasvtji.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtlgwidklx.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtsiaahpbo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtdscucnfy.html

[R73] 分割大日志
来源：http://dali.hammf.cn/Article/details/gtzyqhukeg.html

split -l 1000 big.log part_
来源：http://dali.ivvv.top/Article/details/gtcqbkfayh.html

[R74] 批量重命名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkxfmamh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jiagoushi.top/Article/details/gtvqnhvmjp.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gteqpsvnwv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtzupoizhq.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtacgcwvyn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtoohwaqbe.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtqfihjtkl.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtpdlojupw.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtsrnbnukb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtoqsutdsf.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtqigwwsey.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuanzhike.top/Article/details/gtlogtetdd.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtqzessmfo.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtdpsfqtug.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtlhikzphr.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtolpxacxy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwwvbxyob.html

[S01] C：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtyovamtec.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtirqslnww.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtmthmuyjb.html

[S02] C：变量与格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtqapiqmqz.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gthlexpnog.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtghchhoqy.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gtfbkmyobt.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtwmprnvby.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yanxiufei.cn/Article/details/gtltlusauq.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gtifjypbjv.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtudnhoawi.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtaiymyrtm.html

strcmp(a, b) == 0
来源：http://dali.yj20258888.top/Article/details/gtojzsgobz.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtryehtpbk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtiqhyornu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtaqxgjkst.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtofyjayyv.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtnotearpw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtnphredwg.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtcvssfemm.html

int *p = &a;  *p = 5;
来源：http://dali.yj20258.top/Article/details/gtivlazpok.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtdubisxql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtpvlzscnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtatsqpouw.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtqkhtxmjx.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtxkzwqqjt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtdbvvddqd.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtyucqtxws.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gtbxliepdg.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiktwtzdp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtkmixslty.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtnnugzjsp.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtyqgkoyjw.html

[S16] C：位操作置位
来源：http://dali.yj20258.top/Article/details/gtbubuprnp.html

x |= (1 << 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxonpdyls.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtmfnsasfm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuxming.cn/Article/details/gtiwynptsk.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtiykhfaqs.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtkmpgoipl.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtteujctut.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtkqyrfdzh.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtpgqgozpo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbmmiakl.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtomliwbhv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtebdnaawh.html

[S22] C：字符串转数字
来源：http://dali.hywenlv.cn/Article/details/gtxeykkydg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtmrogojjr.html

[S23] C：随机数
来源：http://dali.haohaochexian.top/Article/details/gtxtwjszmz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtdqycuqbr.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtuehcpxaj.html


<!-- 参考信息 -->