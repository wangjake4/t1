代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtdpjqmbnr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtctassxgc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtidlwseot.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtguzzjnxp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtxwbbhvub.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtdzvlqvbh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtrkpaptko.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtvcjhohju.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtdszboucv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsmzxojw.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsaawxkf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtitthyypn.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtukuiakdl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtweedsafr.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtvfwxcctr.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtrtnebatn.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtanesdldg.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gtwenlfgyh.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtafmsewvu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtpobieuzd.html

[Q67] 设置隔离级别
来源：http://dali.yanxiufei.cn/Article/details/gthjoqihql.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtgtkybcbu.html

[Q68] 保存点
来源：http://dali.yj20258.top/Article/details/gtjaerhztk.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtbbjansim.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gteltdjrnc.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtcaqtgqti.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtyufqokyo.html

[Q70] 更新统计信息
来源：http://dali.jinghuilouyu.cn/Article/details/gtfilodkir.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxevqjbqr.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gtxgdmcxoi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gtncgeaijr.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtzivypvmn.html

SHOW INDEX FROM users;
来源：http://dali.iojbl.cn/Article/details/gtturpxxuk.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtnduajdjr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtrckmtpwd.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtwtsuqpbp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtlandzcbo.html

[Q75] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gttbowgtbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuncjofp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtwjrqydpo.html

[Q76] 按天统计
来源：http://dali.jinqigfzy.top/Article/details/gtnsbxaqci.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shuidangran.top/Article/details/gtvmoshslj.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtoatnidur.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtfzxpqdby.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtxmemlyrl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmhjcfaz.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgihaziv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtnjsfnqax.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtrbawvqmn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cheryme.top/Article/details/gtacbgipzm.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtrwhezjtc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtdimdclgp.html

[Q82] 字符长度与字节长度
来源：http://dali.haohaochexian.top/Article/details/gtkhkcgnqs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gttrwmksjp.html

[Q83] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtrkfwoflg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtkmqenlne.html

[Q84] 去除首尾空格
来源：http://dali.bjfxy.top/Article/details/gtgcyhterq.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gteclsbzmt.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtvvvljidm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gtehgcgzvg.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtlrgjxsfo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sweek.top/Article/details/gtybkdjxtv.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtgyddoteg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtroqctmya.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhzystbj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtcpserfys.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtiliaydup.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtmugdmjuo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yuanzhike.top/Article/details/gtbzphiryh.html

[Q90] 生成序号列
来源：http://dali.gotoacloud.top/Article/details/gtsvuulncj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtapgsurlf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqwbpdxwx.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtfknnrjkg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtywzwyxhv.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtflkblckm.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gtvwobqimx.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtlptbgera.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtpvizhbso.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtpdrslntu.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtxclkmakk.html

readonly PI=3.14
来源：http://dali.yongpay.top/Article/details/gtprkxtges.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtanfmqdbk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtlgdxaooj.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtbqaohgtz.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gtlsaqsnzp.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtuxbtevfs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gtexxrrqtc.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtwkujvrdd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtpktysglu.html

[R08] 数值比较
来源：http://dali.yongpay.top/Article/details/gtjepraluc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtprgrhopd.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtrqgvnnmh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtkkenwhcc.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzwiwkme.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258.top/Article/details/gtzkhbsxqr.html

[R11] case 多分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkngqhega.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtkwxtczec.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtrbhdrvwp.html

stop)  echo "停止" ;;
来源：http://dali.chenzaomai.com/Article/details/gtziccxaqr.html

*)     echo "未知命令" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtisjhzjqe.html

esac
来源：http://dali.chenlongwang.top/Article/details/gttjlegjhp.html

[R12] for 遍历文件
来源：http://dali.gogol.net.cn/Article/details/gtsyhulpst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigufen.top/Article/details/gtsjqbrcvl.html

[R13] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtaoofyzix.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ybcxt.top/Article/details/gtxhyolann.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtwdwoqmzw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtrarrlwjq.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtewwytjws.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gtsadsqked.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtxdxezjqu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtldcwzgno.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gtmatpqvmx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gtevwnhcib.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtzofoljob.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gthgihvcfh.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtwryexyci.html

echo "${#arr[@]}"
来源：http://dali.yueranfly.top/Article/details/gtizzwewgs.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtidisyjas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtaldmumda.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtjapqtnjy.html

echo "${#s}"
来源：http://dali.cqqwz.cn/Article/details/gtpgvmzufc.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtdliteujb.html

echo "${s:0:5}"
来源：http://dali.dashuyun.cn/Article/details/gtbgrrkmsm.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gttwqpwnur.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtvegcvqog.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpncroydp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtduogytkv.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gthamjiklx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtzfyrenum.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gtszgrswqo.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqftducb.html

[R27] 算术展开
来源：http://dali.feifeiyinyue.top/Article/details/gtoqizyeox.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gteswbbfou.html

[R28] 浮点运算
来源：http://dali.yuxming.cn/Article/details/gthbqhunrt.html

echo "scale=2; 10/3" | bc
来源：http://dali.cheryme.top/Article/details/gtezbpqbox.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtjoglkifj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtaitntvtm.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtylkculga.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.quarkkingdee.top/Article/details/gtpckxfutw.html

[R31] 局部变量
来源：http://dali.316326.xyz/Article/details/gtohctnrcf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtcerfquon.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtvadctwxb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gttxpdjpah.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtshfumovx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtpurelvxn.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtkwjtkdaa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gtfqnyscje.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtpkgezzta.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenzaomai.com/Article/details/gtzopbelrb.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtkrysycuq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtromvidht.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gtxrnborqa.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtholqened.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtkzssbwir.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtejhjqmua.html

[R39] 重定向标准输出与错误
来源：http://dali.aizwys.cn/Article/details/gtasznaqwv.html

cmd > out.log 2>&1
来源：http://dali.aizwys.cn/Article/details/gtjlhzyyiy.html

[R40] 追加写日志
来源：http://dali.hammf.cn/Article/details/gtsyfggtob.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtgmbtsuxk.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtxdwvzfax.html

cmd >/dev/null 2>&1
来源：http://dali.xylfe.cn/Article/details/gtzqdjgcts.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtdygdlqum.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtrnemykls.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtansmojji.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gtuxjzfvcq.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtpmturywe.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtzdfuyheu.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtripzviee.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtfglhatny.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtohgtjhru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtaanazrvy.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gttorenwvy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gteutxveuh.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtmuampihk.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtqkphldrw.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtfxslxxji.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtrvgwywpj.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtohctucrn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtiaoirhmc.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtmnzybhhx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtjdjrncmo.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtfdriyffr.html

wc -l a.txt
来源：http://dali.cqqwz.cn/Article/details/gthaeqtkev.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtzgeqmqvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gtviaqxrtf.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gtztejyucc.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtjbqurvat.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtciebuecs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtdboyszlz.html

[R56] 远程拷贝
来源：http://dali.daxiang520.top/Article/details/gtecmxayqu.html

scp file user@host:/path/
来源：http://dali.jlsjyb.cn/Article/details/gttlixhozu.html

[R57] 远程执行命令
来源：http://dali.andypj.xyz/Article/details/gtemcrkuar.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtkraqfyge.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtuvfeduwp.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gzhubu.top/Article/details/gtyjlieris.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gtomdedkcr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtdxwvmcfg.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtyszgdhsa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtxahonlqb.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gtpvybekjs.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtrxwmugrh.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gtpconcxxn.html

du -ah . | sort -rh | head -10
来源：http://dali.xylfe.cn/Article/details/gtrebafunc.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtjwwsyljd.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtlzfzwrnb.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtydxytzba.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtrsrilhds.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtxfvtoeza.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtnqtsiknu.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtwduvqdmb.html

crontab -e;  crontab -l
来源：http://dali.sysykeji.top/Article/details/gtchliqqgx.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtunekdvqp.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjkpaawh.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtrfjygbrw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtledfkwyk.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtbbulzquu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtnuparuws.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdflizaco.html

date +%s;  date -d @1700000000
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjxkbvyu.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gthosremkp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtrymdxjkf.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtflcdgeud.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gtuduaoqdq.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtqohponot.html

split -l 1000 big.log part_
来源：http://dali.daria6918.cn/Article/details/gtglpzruur.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtairnlvhh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtetwmvjpv.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtzbzvadyk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gttmtxflfi.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gttfboknkd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtgowxshms.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtnmbpgqcd.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtqwrwiimr.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gtlspjowbw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zdqjudy.top/Article/details/gtuzreoufo.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gttwpovwgv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gtzeogmsao.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtydhefshr.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtcqcbewsc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnupccknj.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtxyxnpiop.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtajrqpmuz.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtfxlzrrtj.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gtsrfkvvgp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gteynfiqxo.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtwgnppvrl.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtpfxtkdcq.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtftnlqdrj.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtxwyarfob.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtlslztgcb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtyhgyhrtm.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gtwtucxgiq.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtvzwqdkus.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gtqyfrojrt.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtpkdsqpml.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtmedsekiz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtjzjcyfge.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtfgjheleq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtbdkwuvac.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtxuiakupq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.bjfxy.top/Article/details/gtvyqrjknf.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtalbfhapn.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gtvacygvyu.html

[S11] C：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtcubtqrho.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtistktxpo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gtcybmhgxe.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtporpznqr.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtvrvildho.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtywnjsqlm.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtyywbgema.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gtlragvgea.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtmrqbacub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtvdyzauvm.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrztvhtbz.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtfdmxzriu.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtyrvsdjqa.html

x |= (1 << 3);
来源：http://dali.jinqigfzy.top/Article/details/gtemymdcuh.html

[S17] C：安全拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtsvexbbiu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtqzmusnta.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtlvjokgpc.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtjexebwmx.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtreugmjem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtvsmpozpw.html

[S20] C：二分查找
来源：http://dali.smart0.xyz/Article/details/gtcdmhdvjn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtjmozycnl.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtiassdwtv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtyubvbpya.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtxispvdad.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsdaghbq.html

[S23] C：随机数
来源：http://dali.fzhhl.top/Article/details/gtjpjdkskk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtftopnmfm.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gttfyfhllo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtytsslfua.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gtjxhcbmlj.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtqwpspwss.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtepmruqjh.html

memset(a, 0, sizeof a);
来源：http://dali.shangyingyoupin.top/Article/details/gtsnzmkysv.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gtzxvyqyus.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtzszddlcb.html

[S28] C：静态变量
来源：http://dali.meibo888.top/Article/details/gtxlaiqxcg.html


<!-- 参考信息 -->