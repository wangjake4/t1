代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtkqievbax.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtehjwwsqa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtqwshjhgb.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuewugsl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtgyyhtcbw.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gtvgifyiso.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtcolxeiqm.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwnqeovff.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtaaaxlmwy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangdashe.top/Article/details/gtyhnnfjqx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtjqonbyur.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtzxjpyfhn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtsczoqqmo.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtzktvoveb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtcwcllkoi.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtysnwhioz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtbyqbeltw.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj202588.top/Article/details/gtidcvqkqh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gtwehsgoqo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gthrwoeygb.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtqjlhvfli.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtaswkzfvx.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtepzpltgh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtduppfsgf.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gttsjunzpf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gtdfkcqufc.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtlcswfojc.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtjhnuxfwd.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtldfmjfqp.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtgzhoeqfw.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gttqyahhby.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gthalcgvdu.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtdvbdzgry.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtneoinpbq.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gtnxazduvl.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtippogjzr.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gtauompleb.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtwyeowlqw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gtocekzbqm.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtfbozmtsh.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtrngsgzqh.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtxcaeznqa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtlmktbdbv.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtotabpugg.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtkekaetea.html

[Q73] 查看表状态
来源：http://dali.shangyingyoupin.top/Article/details/gtbbcpkgdr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gtonhzkrgd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gtdykfqqvx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gtvnahpclh.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtshmdpdnr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtfwezevvl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtnygrtzyj.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gttexvpkua.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tanke756.top/Article/details/gtvhyhxprp.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtmxkwufye.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gtsjqyyyhv.html

[Q78] 当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbpcbqkw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gttzteblyk.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtfixxdhmg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtgznnndwl.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtpiwinfkx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtfcpldoqo.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtrqvcdnwb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtezqtnthd.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gtrzcmlwlk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtsngvzndp.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtwbljvgcj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtdscywwye.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gtksqixwcr.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gttkroakuy.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gtqspgzebn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtsdsvgnxg.html

[Q86] 读取 JSON 字段
来源：http://dali.xylfe.cn/Article/details/gtimecytqp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hammf.cn/Article/details/gtoknijhfg.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtsdrhlgtu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtouykqykx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtmutidohx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.aibaodan.cn/Article/details/gtdsgaoopv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzylulvda.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtoxjpdged.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.wangshuangyany.cn/Article/details/gthcplfgme.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqaxwrzy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gttbhsbpbu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnhtlylhh.html

R. Bash 专题
来源：http://dali.jqgufenzy.top/Article/details/gtntrgsukl.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthaytyvtp.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gtdxwnfctu.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtlpdmaooz.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtgnuyekgy.html

[R02] 变量赋值与使用
来源：http://dali.hfpthk.cn/Article/details/gtfyfwprvm.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtkiewarhl.html

[R03] 只读变量
来源：http://dali.zhengqikj.top/Article/details/gtgaeidwyb.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtmoofawjf.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gtqbonjgwh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtiikhyeuz.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtkisinwze.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtuhtmazro.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzcozard.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gtnblbicaq.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gtrgenngyf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gttslyzpxy.html

[R08] 数值比较
来源：http://dali.ybcxt.top/Article/details/gtilsvdfhr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtrwmuwidq.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtsvgeccmo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fengsongda.top/Article/details/gtcnisezmj.html

[R10] 正则匹配
来源：http://dali.xuanzx.com/Article/details/gtriuvmcal.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtsbcjxzdb.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcveomlb.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gtkycwnkyw.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtanmwuwml.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsjqtijf.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtzqqxgefc.html

esac
来源：http://dali.cqqwz.cn/Article/details/gtixcvlggx.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnzfmblw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daria6918.cn/Article/details/gturpjobwo.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtnhzdwfgi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtcmutlqeu.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gtnjywtrcz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gthygcwqhg.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gthttgunkq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtvpbwjdsi.html

[R16] until 等待条件
来源：http://dali.gzhubu.top/Article/details/gthyokojht.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtzscpiklh.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gtbewurcio.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtzkecaqgz.html

[R18] 遍历数组
来源：http://dali.hammf.cn/Article/details/gtraeungfg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuljwpbun.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gttyfvvpun.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtnkabjjew.html

[R20] 关联数组（字典）
来源：http://dali.zdqjudy.top/Article/details/gtwndkmasj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gthdkfpiha.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtfnfikwhi.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtipuviurc.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtoksaoxyf.html

echo "${s:0:5}"
来源：http://dali.bjfxy.top/Article/details/gtunjlkhxz.html

[R23] 字符串替换
来源：http://dali.yongpay.top/Article/details/gtfrvsqjsx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hnqzz.top/Article/details/gtvwbwzlqu.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gtfvepyerm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtkaxpsqbf.html

[R25] 去后缀 / 去前缀
来源：http://dali.andypj.xyz/Article/details/gtgxhouiai.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpvqgtij.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gtytfmnfnz.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtloquxudy.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gtfiyxxwuo.html

echo $((1 + 2 * 3))
来源：http://dali.sysykeji.top/Article/details/gtrenixoqx.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtpsrdcbtf.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtpixvafyz.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtkorjfveb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj202588.top/Article/details/gtsctbjdvu.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtguiqhhym.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yongpay.top/Article/details/gtqekdqxrg.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtwryboaof.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtucncqklh.html

[R32] 参数个数校验
来源：http://dali.haohaochexian.top/Article/details/gtacxbdsjd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtaxvenjux.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gtepofhblm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtugedihck.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtzfsanglv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.havefunace.top/Article/details/gtcnvvxqgd.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtaeczfztq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhongyouzk.top/Article/details/gtejptsctr.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtjmpllyuh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtamfxkufk.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtavgccsnr.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gtlayzgdpi.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtahvlbjug.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hfpthk.cn/Article/details/gtqhkynnan.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtfqccfuxn.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtvbxdyqqo.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtmghycjte.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtfabezryf.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtrmoalkcc.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtkvhdzsgo.html

[R42] 输入重定向
来源：http://dali.cdnleiting.top/Article/details/gtawrkqkst.html

wc -l < a.txt
来源：http://dali.yj20258888.top/Article/details/gthocsmvyg.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtzaicqpwr.html

find . -name "*.log" -type f
来源：http://dali.dashuyun.cn/Article/details/gtocwdithw.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtedbufxrx.html

find . -mtime -7 -type f
来源：http://dali.yj20258888.top/Article/details/gtjqbbzuzq.html

[R45] 批量删除
来源：http://dali.jianghu66.top/Article/details/gtlglaayfv.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtwjdsnedw.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtfzaykfpb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtzpcwgkfx.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtwcdgsmbb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtgdqyccoh.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtinetadse.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtmmsdglap.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtbycniynj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtxcacfatc.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtdzxppyzu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtbbrtoaod.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtscbgqraa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtrobvazmn.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtzdnzwyow.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtczeflgch.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtdndoxqup.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gtghgcjjkk.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gtamxueuyf.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtoesusqhd.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gthmygaabt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtipuabrtg.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtgbdbglqo.html

scp file user@host:/path/
来源：http://dali.gaohongyu789.top/Article/details/gtwjqduwmp.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtborhwyal.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtervoqgdm.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtbtmeltgn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtzxumwgcw.html

[R59] 发 POST JSON
来源：http://dali.dashuyun.cn/Article/details/gtbxxclvgm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.smart0.xyz/Article/details/gtkjmzicwd.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gtrkwudkcz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cheryme.top/Article/details/gtlnntnwdk.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtcksfvupb.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtgcekehgo.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtfnxogthx.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtrfelskqx.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtorehteyf.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtcgldovnu.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gtucveuowf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtdgmtcpty.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtpjipdbdl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhongyouzk.top/Article/details/gtlqjkqgmj.html

[R66] 定时任务
来源：http://dali.yj202588.top/Article/details/gtycdqfjxi.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtledyxqle.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtclcxmqnr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gtcxylwpwz.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gtezmnwnps.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhengqikj.top/Article/details/gtjfdptwmo.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtgfuauemy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtuevruxfh.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtcpoxctlv.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtowacjybb.html

[R71] 日期格式化
来源：http://dali.sweek.top/Article/details/gtyobmwzga.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtipeyimbo.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtllxgjffb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gttgwnudev.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gthddrkvyt.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtgjbirwix.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtvclueges.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ydzc1.top/Article/details/gtsaihhrao.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtablrnrdl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtdippslim.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtgzcuggit.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtirbdgdxw.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtmpgvtfhy.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtpwfatbww.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtvgviltwn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtneqtzwrf.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gtrdflyltu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gtaegkrckp.html

[R80] 查看脚本执行耗时
来源：http://dali.dianchejie.cn/Article/details/gtmnzttqtk.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtklfhzgwv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtrrjijmur.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtjrznvuon.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtpmzejnwn.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtvlqltyhe.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtljcvcbff.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gtesgtwmby.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtgkhqpokt.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtwguwglri.html

[S03] C：读入整数
来源：http://dali.zhixingplan.top/Article/details/gtwitwxcfw.html

int x; scanf("%d", &x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjqgkkau.html

[S04] C：字符串复制
来源：http://dali.sufxvd.cn/Article/details/gtmcmgpnde.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtqupzonob.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtisfktryx.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtueiejaxb.html

[S06] C：字符串比较
来源：http://dali.ydzc1.top/Article/details/gtkpktfwek.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtcwsiailr.html

[S07] C：数组遍历求和
来源：http://dali.zhongyouzk.top/Article/details/gtmawzynho.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtbtmvjedp.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gtxqpivbwg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtpqvafwju.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtomyqmqvt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtmkmbvaav.html

[S10] C：指针与解引用
来源：http://dali.daxiang520.top/Article/details/gtkgntfxkx.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gtbxnhawos.html

[S11] C：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtixgbnwmb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtbmlxpnjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gtbmbvmwsa.html

fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtydtrpidn.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gthcriivoh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258.top/Article/details/gtudpgcuxf.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtorjoatje.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtlbvqqnir.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtkomvzuwu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtbhfneudw.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtmoeqzoyg.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtdpxbcfts.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtfabzydfv.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtxltwsnba.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtmckszibl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gticnwqqyn.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtrfeivojo.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtlodnnqoo.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gtapvvzwwn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtivnexjlv.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtabjubixf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtzafrhaft.html

[S21] C：字符类别判断
来源：http://dali.dashuyun.cn/Article/details/gtfdfuoyoy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.iojbl.cn/Article/details/gtnofkopim.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtohhtuerl.html


<!-- 参考信息 -->