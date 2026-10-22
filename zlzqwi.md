代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zycfv.cn/Article/details/gtxozgyzvq.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gtqilydfab.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gtpeyquzng.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdovumui.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtcscmjqxw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtulzqpqap.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyzxggnh.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtpxvfqoqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtfgavqkod.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtxjchfyyw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gtwcfqluwl.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gthkjshddx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gthitqjgbl.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtdnhncwqc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtichncfyu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtrzutkjpx.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gtrrzhbxoh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtkapxxiyh.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gtmimcdows.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtbddrcepi.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtvqbheyop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtnzupyctp.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtpkcogjrh.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtzmlqzmnt.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtekohmgod.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtrvdpwdal.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gtktyhsnjl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlkayrkj.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtgvpelgto.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtvufmknys.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtusedvfof.html

SAVEPOINT sp1;
来源：http://dali.zhengqikj.top/Article/details/gtqsihhflx.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtscnwkkhu.html

[Q69] 查看执行计划
来源：http://dali.fzhhl.top/Article/details/gtguofedho.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtqsdpnoem.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtutgenfws.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gturhgprpf.html

[Q71] 查看建表语句
来源：http://dali.tian-w.cn/Article/details/gtonaugnvr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gtmkgkssji.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtlgtvuxap.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtugujicko.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtxcaxyeup.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gtpkkfnaji.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtohdjchkv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fengsongda.top/Article/details/gtouudmktr.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gthanartpm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtmvhdrxqy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtgegeotmx.html

[Q76] 按天统计
来源：http://dali.hywenlv.cn/Article/details/gtdknqgkzp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtzxnkzsiw.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtdwgjpstc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqytikon.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtkvkjjfwc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtfaqdwtmm.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtkbhyxsgt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gticpdlzzv.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gteqvrllgz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtdfrchizz.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtvuahiesy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzlzxohqs.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtnmvgpsnx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtmmljrxdr.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtamejgubn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtksfmiide.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtlkolfxas.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gttmhwftxw.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigxjilqd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgufenzy.top/Article/details/gtrgdrebow.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gtzodyhgcr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtferqogdj.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtkdfrswdf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtdscwphyx.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtjlvllxdr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gttjiuilor.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjhiaygow.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtxtjlbhrz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtpvoumuvt.html

[Q90] 生成序号列
来源：http://dali.nanxinkj.top/Article/details/gtqiqkuqsf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangshuangyany.cn/Article/details/gtpippzcbz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtasyhxfyw.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtdkotnlku.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbnwptopr.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteiwtujzf.html

#!/usr/bin/env bash
来源：http://dali.aibaodan.cn/Article/details/gtegtccrte.html

set -euo pipefail
来源：http://dali.jinqigufen.top/Article/details/gtjsuwgomx.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtwesvqqyn.html

name="Tom"; echo "$name"
来源：http://dali.daxiang520.top/Article/details/gtpfuithjh.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzrauefhd.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtzjhnhsmx.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtdjieukyx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gtazvsksho.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtlbsgrtcu.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtxcodljxs.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gtbbgurcfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtplqamnwn.html

[R07] if 判断文件
来源：http://dali.aibaodan.cn/Article/details/gtytzziuyl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtapkchgff.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtmaqcithj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cqqwz.cn/Article/details/gtxeggzyzf.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtgkbzhqmd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jyoumei.cn/Article/details/gtangdbrek.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtyufazhno.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtbliiatis.html

[R11] case 多分支
来源：http://dali.ydzc1.top/Article/details/gtyqvexsqd.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtmfraxnmf.html

start) echo "启动" ;;
来源：http://dali.0kj1m.cn/Article/details/gtgkoealvf.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gtkqldjfol.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gtlezfmonl.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtdspvderf.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtvoxethkt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgdwahgo.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtooujbfdl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtqoxbwehp.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gtpsgbegnw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtzkqmbxmd.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtboyfkpaq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtvaydxnoo.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gteiscjlqm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtwidyjeoh.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gtqxdmkqak.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtlzzoqyny.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtfuiigkxm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtsyzhzvky.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtqtuxtavn.html

echo "${#arr[@]}"
来源：http://dali.xziqi.cn/Article/details/gtbfppwqrk.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtfallsuuu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgufenzy.top/Article/details/gtydmaaoaq.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtpbbkeqqj.html

echo "${#s}"
来源：http://dali.dashuyun.cn/Article/details/gtawmcoffy.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtqnhteffq.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gthrnmnfve.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtkbfcwyso.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtjigjbwfq.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtmvqygmcq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtstbczwyi.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtfvttyvcj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gtgmbrelvv.html

[R26] 命令替换
来源：http://dali.sysykeji.top/Article/details/gthkyeoith.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtympwtcws.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtxewydidz.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtuzihfhtn.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtigdtqojo.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtmfkvnpfn.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtdyjimysp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangdashe.top/Article/details/gtjanrarec.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtziyyohdx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtwhatvhwc.html

[R31] 局部变量
来源：http://dali.redwolf501.top/Article/details/gtgrfzndvw.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfxmczeql.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtlvpfbfcr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gtuoabenys.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gtwuiiwung.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtknioldib.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtaudaauqb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtlbsfydoy.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtaetrtjpz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.0kj1m.cn/Article/details/gtvfzelkdv.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gtknyjsxqc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtqvhfqstg.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtyxhuixnn.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtmzwqorub.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtkbegcujy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtfepsvrmc.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gtgjacyliz.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtnfukdvdu.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtzjmbtakj.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtuogqmmrm.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtvlfulxyv.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gtudevuvyf.html

[R42] 输入重定向
来源：http://dali.snrcjt.cn/Article/details/gtujigdqiu.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtrmynajdj.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgrpjvyo.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtsufvjgjt.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtxwevvwhf.html

find . -mtime -7 -type f
来源：http://dali.aizwys.cn/Article/details/gtgbxqxbcs.html

[R45] 批量删除
来源：http://dali.hongshengwenyu.top/Article/details/gtujlajosg.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtsrnsktzo.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtmslawxgf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtxmeiasxm.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gtzossjhmb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuxming.cn/Article/details/gtadujjixc.html

[R48] awk 取指定列
来源：http://dali.316326.xyz/Article/details/gtbceazswj.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtkjuuumaq.html

[R49] awk 带条件
来源：http://dali.dianchejie.cn/Article/details/gtuhwkjplr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangdashe.top/Article/details/gtpuvkxtpi.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtggxfsrrb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gthrliohsl.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghcfxdnp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtvflacogr.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtmfwxzvpy.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtgkvxzkra.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtynzsokti.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtjttggpfw.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtvzfonvsf.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gttmbpqqlm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gtjqcdkrli.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtrtfmmwbs.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtcyaurlcr.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtparmcxsd.html

[R57] 远程执行命令
来源：http://dali.gogol.net.cn/Article/details/gtogeccpae.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtogqhixbf.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gtkypwanjx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtkadycdvh.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtxuytvndr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gttauljxos.html

[R60] 只看 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gtcnjyjgvi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sweek.top/Article/details/gtpyzcgreg.html

[R61] 磁盘占用
来源：http://dali.xziqi.cn/Article/details/gtgdbuzbha.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtvxotifgt.html

[R62] 找最占空间的文件
来源：http://dali.chenzaomai.com/Article/details/gtslicmbkr.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtnflyxouq.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtxqphemgw.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtgyslmyxc.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtpnjzqgtb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gtvgvokydr.html

[R65] 查看端口占用
来源：http://dali.wangdashe.top/Article/details/gtrxsajaua.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gtcjqezydr.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gttemrigvm.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gtskeveefv.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtrviyjeka.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtupcedfze.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gtlhdfbpzp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtplwgtjwk.html

[R69] 生成随机密码
来源：http://dali.smart0.xyz/Article/details/gthkoigtpt.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtvdgphdtg.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gteiitsgvo.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtjsmguybp.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtzoboldjs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtrclgcqtl.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtgwgaeiab.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtlxnpgtox.html

[R73] 分割大日志
来源：http://dali.cashguo.top/Article/details/gtwtvsmrep.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gtfwejwzih.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtczkeuumj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtjykmgygj.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gtkynyqeuj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jianghu66.top/Article/details/gtdidtrwdb.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtqicvermk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtookzievs.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtcpocvoye.html

read -rp "请输入: " ans
来源：http://dali.yanxiufei.cn/Article/details/gtxbxojupz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gtfpmseeuu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigfzy.top/Article/details/gtvfgiynqk.html

[R79] 解析命令行选项
来源：http://dali.shzxlz.cn/Article/details/gtvwhayrgu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtdoerfenb.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhownzam.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtvtiqszdh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtljstjhtr.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtxurtuush.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtakmsylwg.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtqywmdckw.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtggxnmpwj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtufmyhscd.html

[S02] C：变量与格式化输出
来源：http://dali.mhx1999.top/Article/details/gtjoixfhgc.html

int a = 10; printf("%d\n", a);
来源：http://dali.aizwys.cn/Article/details/gtneswgdnx.html

[S03] C：读入整数
来源：http://dali.dianchejie.cn/Article/details/gtxqhddwsy.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtscvcntht.html

[S04] C：字符串复制
来源：http://dali.birdmap.top/Article/details/gtobqzuckz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtcubhzgvu.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtgpumazyn.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtregfvfxw.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtpovplunv.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtbnkpqead.html

[S07] C：数组遍历求和
来源：http://dali.dashuyun.cn/Article/details/gtdrkkipuw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnrlruhj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhiwuduotai.top/Article/details/gtitkvcgzi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtfmcsfhbh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhiwuduotai.top/Article/details/gtecnxuurr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtgcxpylta.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtizfhjcsf.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gtnjkkepag.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtvpwphenc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtwwjwqdkd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtwkkhflza.html

fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtbzfsveum.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtfpzioioh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gttmqyiaiy.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtqttinffi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cqqwz.cn/Article/details/gtxycyzemm.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gtuwdbyvmz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtkafqozup.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gthbcmbqsl.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtnipshcqx.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtldrbdlec.html

x |= (1 << 3);
来源：http://dali.aibaodan.cn/Article/details/gtlsrclbfw.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtfpiryqta.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtwgtrilhe.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtelqahtuw.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gttdtnjpnw.html

[S19] C：快速排序
来源：http://dali.feifeiyinyue.top/Article/details/gtubavnafa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtbsbnvisw.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtpttuuasi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtispaklxy.html

[S21] C：字符类别判断
来源：http://dali.cashguo.top/Article/details/gtgbutcufy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtevkrswkn.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtlgllwehk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gtwlfhcgzi.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gtwkrkikxm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtljifemvb.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtllcelvxz.html


<!-- 参考信息 -->