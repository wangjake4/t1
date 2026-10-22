代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtrkdpdisr.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtseesfxdz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gtmipdpfui.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtpglzjyww.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtrwxexfja.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtqqwououd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gttsqxmhfb.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gtwzeevrgd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtzyhqeduq.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtftfrnzmw.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gtzsuxawkw.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtjrkvpgnh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtalxmfokw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtwkefjvnf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtlnxmgdhu.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtgmrqmous.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtljcoydui.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtvusbkyup.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtwaiiatzh.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtmtvtftzn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtgwutyzij.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gtgndtqtdz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtppgxxpri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtobewscok.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtrlahhbsw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtaxsrwcva.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtvluoledq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsosabjes.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtxptptuov.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtjyfsmoqk.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gthlcwmnzx.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtfdrxkkam.html

[Q65] 回滚事务
来源：http://dali.hysaishi.cn/Article/details/gtokmrnddg.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gtfxrjkqid.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtzpcywvsy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtvfvnayjp.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtscyrmupy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtfbvrayth.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtlculsnps.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtfluhnwfv.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtgzvvtgpc.html

[Q69] 查看执行计划
来源：http://dali.zhongyouzk.top/Article/details/gtjpfmkoro.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtgrhmyuxi.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtgxserekc.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gtipbcecjs.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtxqegrymb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gtulyacmmg.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvwfzbzq.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtatjhammr.html

[Q73] 查看表状态
来源：http://dali.redwolf501.top/Article/details/gtgecdlkmb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtphhedfjp.html

[Q74] 强制使用索引
来源：http://dali.cucudq.cn/Article/details/gtynbnivco.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtnwjyemyz.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gteqmykuoc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtyyhdbchu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtrzesknbw.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtlvaocfua.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtyodviujn.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gtxjkypsuy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gtwrthknkb.html

[Q78] 当前时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gteoigiqhb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncolntxi.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcbdwuwj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgufenzy.top/Article/details/gtmsfwkkge.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gtmgpzzoue.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtfjyavzah.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtxvlzmeco.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmncilns.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gtnvggnvxh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzihxyjd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtrzwlbugz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiluaxig.html

[Q84] 去除首尾空格
来源：http://dali.zhiwuduotai.top/Article/details/gtkurtsjoy.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtkfgkilsb.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtqgpxtqdj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gttxtlqtjo.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtvwrtlwml.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtlqlhjwex.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtyibgltky.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocrqcboo.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhoulong.xyz/Article/details/gtyjiiqxwf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtpdpbvqwq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtmyythxlg.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gtxngveeqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtynvtawch.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtnmpyuiwc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtzqdtmwwo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvofgrpgc.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtkekegatr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtslwecsyg.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtyijlavaj.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtiekcyumq.html

set -euo pipefail
来源：http://dali.zycfv.cn/Article/details/gtyomldely.html

[R02] 变量赋值与使用
来源：http://dali.chenlongwang.top/Article/details/gtkdjrnmil.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtygqdobqb.html

[R03] 只读变量
来源：http://dali.tianlin.xyz/Article/details/gtdbwtppph.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtzkzmlioe.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gthrfbdzas.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gtnyjnohba.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtgruubfnp.html

name="${1:-default}"
来源：http://dali.jlsjyb.cn/Article/details/gtrybytwki.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtgprxquuy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtqsdwpcph.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtimchmplc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtefjhtpih.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtcanddymx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtidsuyavi.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gteextsxkx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtnhrptguq.html

[R10] 正则匹配
来源：http://dali.yj20258888.top/Article/details/gtgruqhtrw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtvkdhqfhx.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtjotdvmhw.html

case "$1" in
来源：http://dali.yuanzhike.top/Article/details/gtfvrhgine.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtadqzykmq.html

stop)  echo "停止" ;;
来源：http://dali.sufxvd.cn/Article/details/gtktxwdcwl.html

*)     echo "未知命令" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmdfijjw.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtktmyfxhr.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gtmpdbxfgr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtqjeidxka.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gtqwqlzkge.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtvlkuznkj.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtlhpylmqo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gttpuenjyn.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtpwyyeknc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtqdnaiche.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gthtghaeaz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuxxsdls.html

[R17] 数组定义与取值
来源：http://dali.guowangkeji.top/Article/details/gtoydadbex.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.birdmap.top/Article/details/gtkhfpciaq.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gthepkeufq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtpggcvyjh.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtjwpkdisz.html

echo "${#arr[@]}"
来源：http://dali.yvedp.cn/Article/details/gtyfqowrfs.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtuzeswxyl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtafhlhxjl.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtxejzxxnu.html

echo "${#s}"
来源：http://dali.iojbl.cn/Article/details/gtdvfrckas.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gthujhkvbh.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtxoqzysss.html

[R23] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtgrznduao.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtowmdtvum.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtghzsrhqf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtvgpqmhhu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtisxswtrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtsgopcxic.html

[R26] 命令替换
来源：http://dali.hnxiangtu.top/Article/details/gtumxjuoje.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtzhxopruh.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtpmrekwut.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gtsabvappo.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtxnfhuulr.html

echo "scale=2; 10/3" | bc
来源：http://dali.sufxvd.cn/Article/details/gtloaohlbx.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtewhkzoss.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvjlymed.html

[R30] 函数返回状态码
来源：http://dali.yueranfly.top/Article/details/gtwpyqllte.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.vqdsnc.cn/Article/details/gtrhblbclu.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtdejzsyjb.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtidbzgknj.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gtapiajmwy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtujntczlr.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtpylokoyn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.quarkkingdee.top/Article/details/gtrcctpmdx.html

[R34] 退出时清理
来源：http://dali.yongpay.top/Article/details/gtbhkphwsw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtjjjesmyo.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gtoilzuabk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtrosppzko.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiwglyae.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtsqghgaap.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtafmkjiwy.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtibmfpcjb.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtshgztqzp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtlzrlhtyj.html

[R39] 重定向标准输出与错误
来源：http://dali.316326.xyz/Article/details/gtisrbwzmo.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gttobgyeoe.html

[R40] 追加写日志
来源：http://dali.chenzaomai.com/Article/details/gtpozeomne.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtnhyalojz.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtkdnupzja.html

cmd >/dev/null 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtxfnmkkvj.html

[R42] 输入重定向
来源：http://dali.shangyingyoupin.top/Article/details/gtdyjkvort.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gticbmkhvy.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtmpxkolzh.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyhqezge.html

[R44] 按修改时间查找
来源：http://dali.smart0.xyz/Article/details/gtdfkxrcxz.html

find . -mtime -7 -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbpyqaab.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpulvprr.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtsnzliygo.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtbgcqhobs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj20258.top/Article/details/gtfikrnqoj.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtddnqcsao.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtnpocatjp.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtpucnmdhx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtejaxntkm.html

[R49] awk 带条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtutgxrkoh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.birdmap.top/Article/details/gtkwavdqbh.html

[R50] awk 求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuvqirth.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtjhggvzbf.html

[R51] 排序去重取前几
来源：http://dali.316326.xyz/Article/details/gtqdgugnro.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtbrpoclpv.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gthclbfhuf.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtggdndrcu.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtnzumtolz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.316326.xyz/Article/details/gtxamecupy.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujegwdhw.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtjsnsmgrz.html

[R55] 压缩与解压
来源：http://dali.ydzc1.top/Article/details/gtjrixvhoj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuecynttv.html

[R56] 远程拷贝
来源：http://dali.nanxinkj.top/Article/details/gtywihxgyp.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyhwtsjp.html

[R57] 远程执行命令
来源：http://dali.quarkkingdee.top/Article/details/gtmcxqrnov.html

ssh user@host 'uptime'
来源：http://dali.zycfv.cn/Article/details/gtmwjfjpaw.html

[R58] 下载文件
来源：http://dali.aizwys.cn/Article/details/gtjhsrkdfg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhoulong.xyz/Article/details/gtxzayewkl.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtnoportyh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gotoacloud.top/Article/details/gthwngfjig.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtptljozif.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jqgfzy.top/Article/details/gtqjthjrrw.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtnvcczgtq.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtmzecbdom.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtzatnkwvd.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtvtotnchj.html

[R63] 内存与进程
来源：http://dali.hongshengwenyu.top/Article/details/gtrguqbxge.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258888.top/Article/details/gtpzvenqyh.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gtkgwdydxm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtdffdlkdw.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtnpcohicu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yongpay.top/Article/details/gtiygosjtu.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtoswdtajw.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtmjgymuah.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtfayrmdhz.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtnaicxnfv.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtnhdcgldg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtypwekmit.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtckmwlxol.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gtxwslgnba.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtomippqtx.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtjajoojhc.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtoykluqgx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gtbpmhgcne.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtabqvrnbh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtokgnlgfp.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtgvtuezpx.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtfhjodikm.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtuweumcya.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258.top/Article/details/gtlfseyipv.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtedfduspt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gtmmimpamg.html

[R76] 使用临时文件
来源：http://dali.jinqigufen.top/Article/details/gtzvpybxhu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtqbivsjfy.html

[R77] 读取用户输入
来源：http://dali.ivvv.top/Article/details/gtkccvioho.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtesfzdxdp.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gtlsthyplr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtlxychkjl.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gthzfxlooa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtldeloldh.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtcpbcyyck.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtuaqvbxvt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvlvamegt.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtimdqfhao.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvtnhyivp.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtztdkohhq.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtnyzhsybi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtgletztbs.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gthsefxsnd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelsdypjp.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdtbsdgr.html

int x; scanf("%d", &x);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyzdedjv.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gtgahdmxfq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtgiqqbzkw.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtzsrfnvzu.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gthxnqsrpk.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtmirvqjyu.html

strcmp(a, b) == 0
来源：http://dali.xinyue.icu/Article/details/gtezzipimn.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtnxyfyjgx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtzobiydae.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtuibaxrwh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtxbsovrjr.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtyzzfeomz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtaxrsxtlu.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtjljoheli.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmxhjuzs.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtdjkttqzm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtapjslwyy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtabvbhlmc.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtjtdwkymp.html

[S12] C：写文件
来源：http://dali.zdqjudy.top/Article/details/gtfuuxlxvt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gtualwomvj.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtgimxcmmk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtrensuwtq.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtjwygnbxf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtwzdcqhjh.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gtslvtjbai.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gtcjirnivq.html

[S16] C：位操作置位
来源：http://dali.vqdsnc.cn/Article/details/gtvondgjzz.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtycqevvmj.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtlkcqhzvf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenjidiqi.icu/Article/details/gtemxyidvo.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtsiaakfrj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtuekpvvfg.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtwzvtivii.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtuxuejrbp.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtoxkrjshc.html


<!-- 参考信息 -->