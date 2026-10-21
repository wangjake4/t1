代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtrrbgblit.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtelgorzwj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagizvzqt.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtevqewvbi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gtcgbcruai.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtfxrstmzm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gtvxzymkne.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtgaxyuexz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtzvxyfzef.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtywvxfgua.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtagazfnvx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtvqeululn.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtfuazxrwp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtruizssbc.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtjhpjrpqr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtwbmqqmlw.html

[Q63] 开启事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvyxmkik.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gtflstrjiu.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtjckrjsah.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtkiqcgrfn.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtktignwrf.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gthnwjkrqz.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtzuvyqhti.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtzyzqgjxr.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpphvhfns.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtarqtpdzg.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtzrhxyzeb.html

SAVEPOINT sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtzwqtutpn.html

ROLLBACK TO sp1;
来源：http://dali.hammf.cn/Article/details/gtrirjjdos.html

[Q69] 查看执行计划
来源：http://dali.9152youxi.cn/Article/details/gtpwdpbmeh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.kuanghao11.cn/Article/details/gtqbbuuppp.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtjhadqegq.html

ANALYZE TABLE users;
来源：http://dali.jyoumei.cn/Article/details/gttmwhcgvw.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtmnuzxlcb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gteqahhghz.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtxfehyoxn.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtugynszde.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtamirtxfw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtigajmovk.html

[Q74] 强制使用索引
来源：http://dali.mhx1999.top/Article/details/gtankstjzq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtqbmnfaqy.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtjmbwrzmi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtnyzzyxbi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtdnbfugmc.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtihcvsvhx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtckkqmbbm.html

[Q77] 时间加减
来源：http://dali.chenjidiqi.icu/Article/details/gtaesqajmq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtqcloyxmm.html

[Q78] 当前时间
来源：http://dali.tanke756.top/Article/details/gtwzrseeah.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ppjwa.cn/Article/details/gtmzkhnjqg.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtynnomgdp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gtsihokpol.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtbrumjgvf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtfpumdcrz.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtrhqeuuea.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gzhubu.top/Article/details/gtucigudvo.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gtaryxewsl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtthhrvnbj.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtcttkarjh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtacunxtkp.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaayqxai.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpyumtadv.html

[Q85] 数值取整
来源：http://dali.yuanzhike.top/Article/details/gtzjfvbkxi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtbtrasafy.html

[Q86] 读取 JSON 字段
来源：http://dali.sweek.top/Article/details/gtvdtsnzbt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gttawzlpee.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtdktzavdm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtpobsjvir.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtqjgkatto.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtghmfjkug.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtyssxwezn.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtjqiccyvu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gtufvbvhrh.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtkhfzdaas.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtqnfdfvtz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbfeeqryr.html

R. Bash 专题
来源：http://dali.fzhhl.top/Article/details/gtbvvihykh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrfjwqkoe.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtmoftrlyt.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtorgmffpq.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gteeyuhigi.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtdmsedmks.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtbhsaxxih.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtdivxlzst.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtodqwgmqn.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtjdsehjyo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ydzc1.top/Article/details/gtvrowzftm.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtjqdlueqy.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtyrbzbpqy.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtbrwralso.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtbvvsfmsp.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtqslhppsj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nwbrower.top/Article/details/gtsnmlotix.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gtmrzyziqk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtkcymstus.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtervxffzu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hfpthk.cn/Article/details/gtxhxcoyyg.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gtuurnpuyb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtpwmphmzy.html

[R11] case 多分支
来源：http://dali.havefunace.top/Article/details/gttiqwkhjz.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gtpmaqazqd.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtoldxdsqu.html

stop)  echo "停止" ;;
来源：http://dali.yongpay.top/Article/details/gtarilrwmy.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtdnfrerkh.html

esac
来源：http://dali.jinqigufen.top/Article/details/gthzgqkvpc.html

[R12] for 遍历文件
来源：http://dali.nwbrower.top/Article/details/gtebhqvbvg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtxyeqfgwn.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gtxaqdkdnq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtaxuucqpu.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gtdijkdtbu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtguelvazz.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtbqsrmrxa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtztldixsx.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtglnbfwgn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gthnuxudnf.html

[R17] 数组定义与取值
来源：http://dali.mhx1999.top/Article/details/gthyksdbsb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aizwys.cn/Article/details/gtfzqgrrlf.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtimvbeikf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxeavibp.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gthmtwfxts.html

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtbfrohnur.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gthzcueive.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gttzkiswjc.html

[R21] 字符串长度
来源：http://dali.yvedp.cn/Article/details/gtzrydfqno.html

echo "${#s}"
来源：http://dali.zhoulong.xyz/Article/details/gtjypnavkn.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gtnqmxlune.html

echo "${s:0:5}"
来源：http://dali.c1oappe.top/Article/details/gtekrzybqd.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtgiagjitq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtntmyaeed.html

[R24] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtjullbgoz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.c1oappe.top/Article/details/gtyjxmhiph.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtcvasawrx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gthbxixxds.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtkiuoyieb.html

now=$(date +%F); echo "$now"
来源：http://dali.zdqjudy.top/Article/details/gtjbevkphn.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtczhpmrou.html

echo $((1 + 2 * 3))
来源：http://dali.shuidangran.top/Article/details/gtgubktohv.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtuegyyceg.html

echo "scale=2; 10/3" | bc
来源：http://dali.yongpay.top/Article/details/gtglfirbuu.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtfexrmeoh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtelycdwkr.html

[R30] 函数返回状态码
来源：http://dali.jinqigfzy.top/Article/details/gtuqttmeha.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.wangdashe.top/Article/details/gtdzznwoad.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtrfgonyky.html

f() { local x=1; echo "$x"; }
来源：http://dali.quarkkingdee.top/Article/details/gtqcrcvsee.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gtcdwxzfac.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtagbadoai.html

[R33] 捕获错误并提示行号
来源：http://dali.ybcxt.top/Article/details/gtxbuhcjty.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtehuaaoqo.html

[R34] 退出时清理
来源：http://dali.kuanghao11.cn/Article/details/gtzjdbzsuw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtxrdrakif.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtnqhuhvph.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gthcxkuowx.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtwybkjmyn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtvuzmuxap.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gtlaampqph.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gtscfhzuyl.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtmppvaclw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtrzvkiylh.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gttxntklft.html

cmd > out.log 2>&1
来源：http://dali.jlsjyb.cn/Article/details/gtmfhuuylo.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtdeiajcse.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtdsaclpuc.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gtlcsvqjha.html

cmd >/dev/null 2>&1
来源：http://dali.ydzc1.top/Article/details/gtwlxqkmxy.html

[R42] 输入重定向
来源：http://dali.cqqwz.cn/Article/details/gthwkhdqlu.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtqaontgii.html

[R43] 按名字查找文件
来源：http://dali.xziqi.cn/Article/details/gtlhlomkom.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymlsdhrj.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtgvyuwefb.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gtpokvaeot.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtndxknluu.html

find . -name "*.tmp" -delete
来源：http://dali.gotoacloud.top/Article/details/gtfxpmaqmk.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtlbvhquzr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xinyue.icu/Article/details/gtijaqbgcn.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtntkqbjna.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtckuudzyp.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gttgrogbpc.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtjncgbtdf.html

[R49] awk 带条件
来源：http://dali.tanke756.top/Article/details/gtcbwjnpio.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgufenzy.top/Article/details/gtlczoxuev.html

[R50] awk 求和
来源：http://dali.zdqjudy.top/Article/details/gtpamafikb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtipykppvp.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtwrzyekec.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtqqdibxko.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtragnkxvj.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtmobeolvc.html

[R53] 查看文件头与实时尾
来源：http://dali.jianghu66.top/Article/details/gtdepxbcqs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtgxnkwkau.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtpgnubnhn.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtxitccnej.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtxikxbnnl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.0kj1m.cn/Article/details/gtobjhbkxr.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtnxhbjqwv.html

scp file user@host:/path/
来源：http://dali.snrcjt.cn/Article/details/gtgnijrisx.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtrfhjuhoo.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gtxskgwohg.html

[R58] 下载文件
来源：http://dali.nanxuanxn.top/Article/details/gtfjwlgcxc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjwtgvbc.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtwoetwsbq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gtzoldhnbg.html

[R60] 只看 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtsxqeqjnk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtmrdlsgbk.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtrhismdsx.html

df -h;  du -sh *
来源：http://dali.smart0.xyz/Article/details/gtyiqrjhqp.html

[R62] 找最占空间的文件
来源：http://dali.hysaishi.cn/Article/details/gtlkqpxwxf.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtipmvvfib.html

[R63] 内存与进程
来源：http://dali.tian-w.cn/Article/details/gthihmiynu.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtjiddlxaf.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gtnrhkkynm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndoptadm.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtrwkjeyec.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtvwtebocf.html

[R66] 定时任务
来源：http://dali.9152youxi.cn/Article/details/gtfllxtidf.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtnqkpletz.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtjfvzxabw.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gtdwcvynul.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gtuwqcacxm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gtjmuxzknq.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gteovfouhp.html

head -c 16 /dev/urandom | base64
来源：http://dali.cashguo.top/Article/details/gtfhoeuoas.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtfgmqvzpi.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtpwaamqss.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtaeolrvhg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtgullqgfv.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtlslhmrgv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gtyywqdjjt.html

[R73] 分割大日志
来源：http://dali.iojbl.cn/Article/details/gtyjzvzxwj.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtyandpzmy.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtjsoilcjq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtigtpuspv.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtahhoyefr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtrgfuwcpe.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gtzcrudwki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtricjtdrq.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtgylzkega.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gtdrjnurle.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtuouccoew.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtazquufzh.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtcooxehvl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shuidangran.top/Article/details/gtumuakpto.html

[R80] 查看脚本执行耗时
来源：http://dali.zhongyouzk.top/Article/details/gtjjtpvkpp.html

time ./run.sh
来源：http://dali.nanxinkj.top/Article/details/gtligoecbt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtfoibnexv.html

S. C / C++ 专题
来源：http://dali.chenjidiqi.icu/Article/details/gtszagykjp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfzrlflpj.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtfvafntwi.html

#include <stdio.h>
来源：http://dali.cdnleiting.top/Article/details/gtvomteums.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gtgiukcxbs.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtartbkofo.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtfvqysfnd.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtrrpaenie.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtsimcutpl.html

[S04] C：字符串复制
来源：http://dali.gaohongyu789.top/Article/details/gtfkxbzgug.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gtpimrchjj.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtfzbbtabu.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtgmjtexal.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gtgajcqosq.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtbjllnkgg.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtglbltujz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.9152youxi.cn/Article/details/gtbphiyoef.html

[S08] C：动态内存分配与释放
来源：http://dali.yanxiufei.cn/Article/details/gtfvvcgvxv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gtnkjmnuba.html

[S09] C：结构体定义与初始化
来源：http://dali.cdnleiting.top/Article/details/gtpmafmdgx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtttbvpzjw.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtrrtuhfnt.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtnoimtelr.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtannhjiqr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtufshtgxm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.redwolf501.top/Article/details/gtlxnlmuog.html

fclose(f);
来源：http://dali.316326.xyz/Article/details/gtoxlwytym.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtybbolhcn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtutdvkrpt.html

[S13] C：宏定义
来源：http://dali.tian-w.cn/Article/details/gtfdynxver.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtwhjppiwr.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gtyewlqoht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtbviegfok.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtdchngrhh.html

(double) a / b
来源：http://dali.zhongyouzk.top/Article/details/gtsxlelham.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtnymldygi.html

x |= (1 << 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtvemtcrmq.html

[S17] C：安全拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvhfimij.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shangyingyoupin.top/Article/details/gturjolxcs.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdaosoje.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gtrpvqqtji.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtsbhndern.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtzuxjtwax.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtujlnypoq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtbxspxriz.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gtkshndfds.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.c1oappe.top/Article/details/gttscgward.html

[S22] C：字符串转数字
来源：http://dali.xziqi.cn/Article/details/gtlcnmofxt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtaxcybfnf.html

[S23] C：随机数
来源：http://dali.316326.xyz/Article/details/gtllwygbqf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxthbfdj.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gtqzciinxe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtahpbdnlv.html

[S25] C：内存拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtntycwqlu.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gtwlsvklrb.html

[S26] C：内存清零
来源：http://dali.0kj1m.cn/Article/details/gtpckskjqz.html


<!-- 参考信息 -->