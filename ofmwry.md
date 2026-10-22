代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtyigeiykf.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtxbgbogxb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzwjiosn.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtahvqtjbw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwptajqxm.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtshnlyrac.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtxmcqwirm.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtppezyiny.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtmfkjoqmh.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gtudeeziwy.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtlrsletdk.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcmoutpq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtjfvudstl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtoeawifwt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtmmoiojgy.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtjlareyou.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtjxxwcews.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtulfzxwmk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtftxiikpv.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtxtnfiqdf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtlgzdwuhq.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gtabtqhumb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtrlpojqta.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258.top/Article/details/gtsmrhlrcs.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtspzhjjxf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtllrgmcxw.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gtqocraxst.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtjzwmuuol.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtvitjslcu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtfogwtkic.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtaiqxtswi.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyesdcuuz.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtlyfhjkrz.html

ROLLBACK;
来源：http://dali.zhixingplan.top/Article/details/gtoxsmidnj.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtdszjmgia.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtzqjhrvoh.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtctdstfkt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shzxlz.cn/Article/details/gtsjutearc.html

[Q68] 保存点
来源：http://dali.yuanzhike.top/Article/details/gthrxzovhh.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtvwjsvxfz.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtxmarblct.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtgsquywvw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yonumen.top/Article/details/gtbspxubct.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtdhxwybzi.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gtrbsgbaaq.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gtmyhrjuzv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtgfgqvfrr.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtfqlzrpqo.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttandqqlq.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gtrirhslwl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcskqoyvc.html

[Q74] 强制使用索引
来源：http://dali.cqqwz.cn/Article/details/gtutkeyfgd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenlongwang.top/Article/details/gtvjrmcgmt.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtfeljyqco.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtyagiewzt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtdcffebxs.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtyysfxiew.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aibaodan.cn/Article/details/gtrjzmhbev.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtgevilglp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tanke756.top/Article/details/gtxpvdfjmo.html

[Q78] 当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtepmzycgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtvovmelii.html

[Q79] 字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtddwuzmzh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpkuodtv.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtexeauhcm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtqrahltkr.html

[Q81] 字符串替换
来源：http://dali.c1oappe.top/Article/details/gtyuzmqbok.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtlaswyumh.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gttbjrbiec.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtlfkxiwae.html

[Q83] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtgesvjfix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvvpfdflt.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtaempzutk.html

SELECT TRIM(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtpeuzanhx.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtobvsmcuu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtfohoeaxc.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtrchmukwi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtwwpotokx.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtnfpvlynx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hfpthk.cn/Article/details/gthtspneyb.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtlzmbplia.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztootwfo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtxicnkbms.html

[Q89] 判断表是否存在
来源：http://dali.guannengcc.top/Article/details/gteocbhirc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shzxlz.cn/Article/details/gtxhomyzaq.html

[Q90] 生成序号列
来源：http://dali.zhiwuduotai.top/Article/details/gtepmvolbx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtjbepjqpo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwujcbdol.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtnapajcxp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdyrswzzf.html

[R01] shebang 与严格模式
来源：http://dali.wangdashe.top/Article/details/gtxlygsqcr.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtamltgmlz.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtbexrivdf.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gthdpyuoug.html

name="Tom"; echo "$name"
来源：http://dali.shangyingyoupin.top/Article/details/gtzbmposxq.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtmzfourqf.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gttfknshox.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtoohkyjjv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fzhhl.top/Article/details/gtkcvucrih.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtpknkdfkb.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtysalogdq.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtodbmpxay.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtfomxovnb.html

[R07] if 判断文件
来源：http://dali.gotoacloud.top/Article/details/gtznbkdsnx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtbmgesgos.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnfmptfy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtsrwthgxz.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtoajneevb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sweek.top/Article/details/gtykqiwmwb.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtixzhmzgf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtmlyfrytv.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtekbwiids.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtvizqbdpz.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gtgeygefzo.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtvxwptrgh.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gtiemtbtww.html

esac
来源：http://dali.aibaodan.cn/Article/details/gthiddaxui.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqekonbge.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gttgrghcck.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtpldqnyrn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtfclpujzw.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtoyngjvbv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtwffsgukq.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtbxkagcwb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258.top/Article/details/gtnrnatcql.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtoxekyqub.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtvadbfgtw.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtlgmgoaqn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gtytazrnyp.html

[R18] 遍历数组
来源：http://dali.gogol.net.cn/Article/details/gtxqvyfvsl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtcstlkxop.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gteoxxcsdk.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtiuedwetw.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtzfttuctm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtohirbrfh.html

[R21] 字符串长度
来源：http://dali.hammf.cn/Article/details/gtxzibcpni.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtlwowkobj.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtgaiymbjw.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtyxjqbxdh.html

[R23] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyjoakew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppwtwmuj.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtinflfczq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gogol.net.cn/Article/details/gtyrmptgbn.html

[R25] 去后缀 / 去前缀
来源：http://dali.redwolf501.top/Article/details/gtendpqwvn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtdfwtgiyl.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylsobtef.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gthxwbhbda.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtoxivlsjb.html

echo $((1 + 2 * 3))
来源：http://dali.jinqigufen.top/Article/details/gttqdaajbu.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtaqbrjajh.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtfluuyvph.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvfvvkeuh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtsgtfdlmb.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gtqmehtmwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvsgukgl.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gtumotnilq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtkybvzmth.html

[R32] 参数个数校验
来源：http://dali.zhoulong.xyz/Article/details/gtxvzsalka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtazyokkkm.html

[R33] 捕获错误并提示行号
来源：http://dali.zhengqikj.top/Article/details/gtklpxfhcb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtymhkfnqf.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gteugwmsen.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtthzhnlfv.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtyynhehwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gttjigvged.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtlvzuvyqv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtnevthckd.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gtgcyhowkc.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtaybkyhqc.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtixrjukcv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxzqxssy.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtirthbkpw.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gtoaklmbsw.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gtwtlwkmns.html

echo "log" >> out.log
来源：http://dali.svipenyu.cn/Article/details/gtfoqguadw.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtgwvystrn.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtlnvsovfe.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gthngwygsf.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiteoilw.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtmxgafpyz.html

find . -name "*.log" -type f
来源：http://dali.gaohongyu789.top/Article/details/gtzqcdgbzu.html

[R44] 按修改时间查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywpbriik.html

find . -mtime -7 -type f
来源：http://dali.gogol.net.cn/Article/details/gtbuspsgoi.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtwjlkiwvs.html

find . -name "*.tmp" -delete
来源：http://dali.daxiang520.top/Article/details/gtnaxxwmbk.html

[R46] 递归替换文件内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkffitzy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtbocghrnm.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtjuuuftbj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtwzgfqiwt.html

[R48] awk 取指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtoczmxrdf.html

awk '{print $1, $3}' a.txt
来源：http://dali.yonumen.top/Article/details/gtbsusknbs.html

[R49] awk 带条件
来源：http://dali.smart0.xyz/Article/details/gthkkhwcdu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtjarhuiox.html

[R50] awk 求和
来源：http://dali.cdnleiting.top/Article/details/gtdwezbqjk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtfqscvxad.html

[R51] 排序去重取前几
来源：http://dali.yuanzhike.top/Article/details/gtlgswswre.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtiotzrgbf.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gtmnqoulyr.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtsicvouit.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtihngxapo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtsgmatoky.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtfecrjrkq.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtummifraq.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtbeczqltl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtbvluygpw.html

[R56] 远程拷贝
来源：http://dali.ybcxt.top/Article/details/gtjggehvhh.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gtrifjfhbp.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gthcoayple.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gtbkcqwrtw.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtiytvqddq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gthqwrurri.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtaiboczhl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtxjxgvjdk.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtypkhhavr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtdcuradkb.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtpwjqtlmu.html

df -h;  du -sh *
来源：http://dali.zhengqikj.top/Article/details/gtqfrniqtv.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtykmquxzx.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtfttfyiul.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtggilcpxc.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtjktovsdg.html

[R64] 结束进程
来源：http://dali.birdmap.top/Article/details/gthukefosj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtfhyfqfrp.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gttyugzquc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtxpjhfvwu.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtwwwwpekh.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtqjvggbzj.html

[R67] 生成随机十六进制串
来源：http://dali.cqqwz.cn/Article/details/gtftolbpch.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtimeaazfw.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtblkagbpb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtkektquhq.html

[R69] 生成随机密码
来源：http://dali.andypj.xyz/Article/details/gtpsyygjqw.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtwirbyhxc.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtrouoqpxc.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtqtfnoqhm.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtgtxqiulk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhiwuduotai.top/Article/details/gtumzbnjat.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gtlozpmjji.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtufuugwyd.html

[R73] 分割大日志
来源：http://dali.yanxiufei.cn/Article/details/gtknlvotan.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgknlsngj.html

[R74] 批量重命名
来源：http://dali.daria6918.cn/Article/details/gtacbqthjy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtzmzzlwmr.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtbyhsjtzw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtprrzvtha.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gthtjyewfh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtrunyvjvw.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtjjpewnho.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtzstlexaw.html

[R78] 交互式菜单
来源：http://dali.yvedp.cn/Article/details/gtovkqtwje.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtptahntpe.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtfczvqbao.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtzmnsfuvg.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtajrgsgmh.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gtevboywvp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyafmahwd.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtoxkofvnh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqgdttvpj.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gthcsysjov.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gteijowrmn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.andypj.xyz/Article/details/gtgkrdfuwh.html

[S02] C：变量与格式化输出
来源：http://dali.kuanghao11.cn/Article/details/gttddfonbo.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtsmadgkxu.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtthbnijiu.html

int x; scanf("%d", &x);
来源：http://dali.c1oappe.top/Article/details/gtaigwwcuk.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtzobfunbb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtsopvsrnn.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtzckecgtf.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtofbnwnor.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtaopmqlpt.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gtgpolvuzy.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtddotckiy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtoprdatgs.html

[S08] C：动态内存分配与释放
来源：http://dali.zycfv.cn/Article/details/gtrswrizoo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gtmblkdtlx.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtpgqbylyl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuanzhike.top/Article/details/gtmqjidugu.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtsmffnjfl.html

int *p = &a;  *p = 5;
来源：http://dali.c1oappe.top/Article/details/gtutkvyyav.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtxtgipozh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gteimxkkzy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtfkobkwnd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gtxnpaecsx.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtifqqbxny.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtaupgyxpa.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gtyxefjpqs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gtoggodcvw.html

[S14] C：枚举
来源：http://dali.cucudq.cn/Article/details/gtkzhzrnqe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gtetdfajrl.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtnrvgijcd.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gtejjtbuzi.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gtjtlcbfrr.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gtifmapgiq.html

[S17] C：安全拼接字符串
来源：http://dali.havefunace.top/Article/details/gtupqlngdf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtkpepkzdm.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtaojewhfp.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtdmhwygyt.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqhktfha.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtsgsvycbr.html

[S20] C：二分查找
来源：http://dali.feifeiyinyue.top/Article/details/gtaplzpktw.html


<!-- 参考信息 -->