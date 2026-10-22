代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtoktyigty.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtynhyymek.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gtghmnzxkz.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtmzdkxllr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtrasbkfzx.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gtxoacyukz.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtypxoecxz.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtuwwiodqn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gteeeacelk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gtnwbgwdzr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gtlqpgyqss.html

[Q57] 行号
来源：http://dali.tianlin.xyz/Article/details/gtxllwneva.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtemkcqskv.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtiuppkuzx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtcstwqrjo.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gthegdmcpa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtsfwbyvon.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gtogqiktib.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtdvcjbcgl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtktaetyld.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtemtagqwe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtdnyywasm.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtccdckooz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gttlujjtta.html

[Q63] 开启事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwanarwp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258888.top/Article/details/gtmhmturvx.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtsuhacrxh.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtrnngkdks.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtbuolqbid.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtumpearmt.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtpakvngvs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtkvoefkus.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gthccbzjhm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gthciyycen.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtjzymgfuf.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gthtaonjbj.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtkodvtjul.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtqjtprryc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtfkuiatmw.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtdnpnpvae.html

ANALYZE TABLE users;
来源：http://dali.gaohongyu789.top/Article/details/gtigfhqzxp.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gtufdykpap.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtaehiptgd.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjnqtyyp.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxgdfjkps.html

[Q73] 查看表状态
来源：http://dali.pengpengdd.cyou/Article/details/gtjgodamta.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gttnstoyyy.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtcfhwgagq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gtkglkxrvc.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtovooytrf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtelkwtqpw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtcsrovqfj.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtuwfxvlaz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtwjqpdmim.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtosgwuyhk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gtssfkdegh.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtstmriroh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtnyiyejbs.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtjygqlibd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tian-w.cn/Article/details/gtgyaqvsot.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtkpfovsvj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtvitidcyu.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtvukrfhdi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqntcdejy.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gttagkyoxc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtfzkaltod.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gttbhsmwhv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtsmroajex.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gttvcogpls.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtmlhndwjg.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gthdhfjkmz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gthzjjsfva.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtwmtvfamf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtjllesxwe.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gttrbcdlrc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtxwjwyuop.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvzrkdxw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gteunvzplr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtcegrecxq.html

[Q89] 判断表是否存在
来源：http://dali.9152youxi.cn/Article/details/gtsnntfrqh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtwfekmzxn.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtnhejjvqt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtmiuktiat.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnuuqzidi.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtbjjyoztx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtyhalmwdo.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtxjzwewnh.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtxkeozohd.html

set -euo pipefail
来源：http://dali.sweek.top/Article/details/gtsmvatgwt.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gtwaikmffh.html

name="Tom"; echo "$name"
来源：http://dali.aizwys.cn/Article/details/gtyzfmerqq.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gttmhhkouv.html

readonly PI=3.14
来源：http://dali.zhengqikj.top/Article/details/gthijeaepj.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gtcubfvjjy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkabacejg.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtvkfattsr.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtfjrspnij.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtyzrxelcf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtmbscufyc.html

[R07] if 判断文件
来源：http://dali.svipenyu.cn/Article/details/gtuwibijbx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aibaodan.cn/Article/details/gtjdtwsqcz.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtliaacntj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gteaksygkf.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtcjmipbye.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtfmnmgcim.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtpwmcenvd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sweek.top/Article/details/gtngozhxnc.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtoenwfvfv.html

case "$1" in
来源：http://dali.fzhhl.top/Article/details/gtevyedhzp.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtmiwwghjr.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtegreceli.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gttobfvhso.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtgtsrklxp.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtjikcdwca.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtezptsrdc.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gtufdwkaav.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zdqjudy.top/Article/details/gtdxblismz.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtrmdabdal.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtosolywaa.html

[R15] while 逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtxgdgwzba.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sweek.top/Article/details/gtqkskpnxz.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gtzzbqytxp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtterjqzfo.html

[R17] 数组定义与取值
来源：http://dali.gaohongyu789.top/Article/details/gtrfdwuduc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gttesxnrtj.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtmachkobd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtjhgtatpv.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gttmmxqzgv.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gteowmvvzi.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtpweycddx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guannengcc.top/Article/details/gtpolwhsot.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gtlxoblkks.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gtulnfwfag.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtijqhrhdw.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtpnmepphv.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtdhekdqnr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ybcxt.top/Article/details/gtwkpgzwak.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtvpchvasi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtsxmdwbao.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtvvtcmsdz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtoxiaisss.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjqeabsm.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gtcodrywjn.html

[R27] 算术展开
来源：http://dali.vqdsnc.cn/Article/details/gtymbxdzkl.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gtsdqkwnhr.html

[R28] 浮点运算
来源：http://dali.chenjidiqi.icu/Article/details/gtybdweoiv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtxkrtzqfr.html

[R29] 定义函数
来源：http://dali.yvedp.cn/Article/details/gteoqckulu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.andypj.xyz/Article/details/gttsppfkor.html

[R30] 函数返回状态码
来源：http://dali.quarkkingdee.top/Article/details/gtsjqhejpp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtqwjwspjt.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtetqabsmr.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfalpimc.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtzzktrksg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtjhbkbyds.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtqcuigula.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangtech.top/Article/details/gtupmowhpq.html

[R34] 退出时清理
来源：http://dali.feifeiyinyue.top/Article/details/gtnepxukwi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtkzuctjyi.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtkjgklhkx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gteyfjrgla.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtdmhxhejl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sysykeji.top/Article/details/gtskxvouli.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtuajoojpa.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxagqzhra.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtppcdbhil.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoolyxmsz.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtzmlnjnqt.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtymqvzayq.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtnlfxatdf.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtdsfvmusz.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtrcrhykfv.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwkofdta.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtnkcbjpio.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtmumxkzyb.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtqklaxgsj.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gtkrdgqqms.html

[R44] 按修改时间查找
来源：http://dali.ehwqpu.com/Article/details/gtoiphhtpr.html

find . -mtime -7 -type f
来源：http://dali.zycfv.cn/Article/details/gtqjkkssyd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gtktrhiqiz.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtmgvlslaw.html

[R46] 递归替换文件内容
来源：http://dali.xinyue.icu/Article/details/gtolnreadu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtqsmhsfdl.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtsufwvjpo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.pycfn.com/Article/details/gtnpccguts.html

[R48] awk 取指定列
来源：http://dali.gotoacloud.top/Article/details/gtlhdfbeup.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtollqwojy.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtgrcsqqjy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenzaomai.com/Article/details/gtmoiozgmk.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtofvgvdte.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtlcpovzup.html

[R51] 排序去重取前几
来源：http://dali.xuetiantiany.cn/Article/details/gtndpnaxpf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtfjvplscl.html

[R52] 统计行数
来源：http://dali.cdnleiting.top/Article/details/gtikfbzlan.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtuhlgtauc.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtmldmghsd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtgzdbzohc.html

[R54] 比较两个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaetlvyue.html

diff a.txt b.txt
来源：http://dali.haohaochexian.top/Article/details/gtxdjesjbe.html

[R55] 压缩与解压
来源：http://dali.xziqi.cn/Article/details/gtcxtsmvld.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkagxzcc.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gthinrcmag.html

scp file user@host:/path/
来源：http://dali.svipenyu.cn/Article/details/gtaawoembk.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtqscjgeit.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtxpnqzmjm.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gtfvewfzbz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtbeefyuwr.html

[R59] 发 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtcksbkcpw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtabjuucfw.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gthclecttn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gteehkttoa.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gtiboieczj.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyiugabu.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtsoiqhktm.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtiqlhorem.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtaatvdhha.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgphowdnm.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtmhnmbjtm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gtcjntszwl.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtqirqixaf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtqrjfaplj.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtgteosqbw.html

crontab -e;  crontab -l
来源：http://dali.aibaodan.cn/Article/details/gtoecbmotd.html

[R67] 生成随机十六进制串
来源：http://dali.tian-w.cn/Article/details/gtvndgkgrc.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtjlujjksv.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtxbyaomkw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtfwshhacq.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtdptqckuy.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtffblljyu.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiukaeuj.html

date +%s;  date -d @1700000000
来源：http://dali.pycfn.com/Article/details/gtcasukstv.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtkvlgzzam.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtneefcuzp.html

[R72] 等待端口就绪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrinebwtp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtmvcqdrvm.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlodihtzm.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtpejojwxg.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtiuuryics.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtcgjgmpag.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtwcuuifmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtgfxolpkb.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtkclmqwzm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtorebrapf.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangtech.top/Article/details/gtviwmbnex.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzzrxarx.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gttqxvwnwj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtjsjlifdw.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gttzgcbsgf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnaorwpfp.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtbwrdoafv.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtzypqlocp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzyjjtjkc.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtwrnxgqxa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvxiefuwy.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofmwazrt.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtkryixkoa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtdjmqxums.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gttsubqsjy.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtmpabmjbd.html

[S03] C：读入整数
来源：http://dali.sxryk.cn/Article/details/gtsqrstcoy.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtotgqlrhl.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtmcwubmtn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtmkkwaica.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gtvulpbexi.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtfdpdljap.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtmybnpwce.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gtmtdwntyh.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gtwaugegsx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigfzy.top/Article/details/gtdzvwyddk.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtoaycwxiv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtinmhvdie.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gthzrcrsbn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtsowbdhki.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtjzznukhg.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtpcirlshj.html

[S11] C：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtbpkjltlr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.nanxuanxn.top/Article/details/gtlidzpyhf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtfximakxf.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtfbykwegp.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gthaaowzef.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtkxktahju.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtvavqrwfc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtboujjdtf.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtkvrngwae.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtjlnttlks.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gtvdsmourm.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gtcogcxnsk.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtmjylcytw.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gtzphwjtrp.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtcqfwwije.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtjrmkback.html

[S18] C：命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtiontijea.html

int main(int argc, char **argv)
来源：http://dali.ivvv.top/Article/details/gtymgqbbup.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gthpxiczjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtsaxllfzz.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtztzyfdzw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gteikiekla.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtkoxyidiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fengsongda.top/Article/details/gtwstukrui.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gteaerrgno.html


<!-- 参考信息 -->