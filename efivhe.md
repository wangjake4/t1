代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2crlzyxpw.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gt2jhqyojju.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2enpwczkz.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gt2lxcuyazb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgesvzux.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gt2zvvahjcl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2bknswfam.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gt2trwtijnu.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gt2skpkjwzm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2kshurtad.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gt2hyksuawm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2ijovkezm.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gt2hjzksbft.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jianghu66.top/Article/details/gt2fnwurcbt.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cpsnmger.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gt2narnnawa.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdmjnfhr.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gt2mturrigq.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gt2ikiuxxhw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gt2rgaeffyd.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gt2gkcshmej.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gt2faxdexjg.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gt2mcukatnm.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gt2mgttokfg.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gt2zliwtwas.html

[Q69] 查看执行计划
来源：http://dali.svipenyu.cn/Article/details/gt2vpalfabt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuetiantiany.cn/Article/details/gt2noztqbps.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2apbxlqxy.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gt2tlfujgvz.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gt2ktizlpjj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2wujojiir.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2upuhcjau.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2copewgxa.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gt2jccnjrtd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gt2urdpbjgy.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2odsmwetq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gt2qgsyabkq.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2ilkhfysm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2ojjdievw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tygmidvt.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2malzfndb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.snrcjt.cn/Article/details/gt2yrcdjfwx.html

[Q77] 时间加减
来源：http://dali.vqdsnc.cn/Article/details/gt2nnyttpqb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2meskcdwq.html

[Q78] 当前时间
来源：http://dali.hammf.cn/Article/details/gt2uwbtzayy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gt2adnjdgbk.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2qybcsjbu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cucudq.cn/Article/details/gt2qfyypeye.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2eznsbyqv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2ydevqbbz.html

[Q81] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gt2vtiwqsda.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2rdkprdao.html

[Q82] 字符长度与字节长度
来源：http://dali.gotoacloud.top/Article/details/gt2hygsrhrf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2thiwumjd.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2gtprpebw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2qlvxhnej.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2hxxbbjlu.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2zxfrarpi.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gt2mbeqciiy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udeukjom.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2mghrohub.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdsjhwyt.html

[Q87] JSON 字段做条件
来源：http://dali.vqdsnc.cn/Article/details/gt2aoqvbhfw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gt2uvainkzh.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gt2fqihobdp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gt2ttrifohl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2mslgkdpk.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2qbxpxibb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gt2ldysqroa.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gt2oqnuhdgd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2bcinayvi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ghjrcpgr.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2htuwijfa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2jcoufmtu.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gt2ddtdwdfl.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gt2ixadmzai.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gt2yvlokonz.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gt2ejidaknv.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gt2ecydmcvv.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2stgznpqs.html

readonly PI=3.14
来源：http://dali.tian-w.cn/Article/details/gt2qdmeenvb.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gt2qxlswxtk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gt2ifrvgnyj.html

[R05] 参数默认值
来源：http://dali.yj20258888.top/Article/details/gt2wipuverl.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gt2nzlmbaow.html

[R06] 判断命令是否存在
来源：http://dali.zycfv.cn/Article/details/gt2ihhhpsgd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gt2vcwdeeam.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gt2sfgkrsvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gt2zmlakazl.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gt2ziylpioj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwtqmggf.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gt2cqmjsbaz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gt2yybinkha.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2namfnrdc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gt2cahtxwtl.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gt2lcnhzqed.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gt2cvmbuhrw.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2cangmqyx.html

stop)  echo "停止" ;;
来源：http://dali.yangfankeji.com/Article/details/gt2azutziys.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2hmwcgsls.html

esac
来源：http://dali.yueranfly.top/Article/details/gt2elpjiyhj.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2dpsskclg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tghzcrac.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gt2apmftdzz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2pbdjhred.html

[R14] C 风格 for
来源：http://dali.zhengqikj.top/Article/details/gt2plzxgsqo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2jurruzpx.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnkmbzqa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gt2gzjlrjmg.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gt2ovxthcvs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2ajypspcq.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gt2rubjnogt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.0kj1m.cn/Article/details/gt2amtbfvpl.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gt2knytpmzb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gt2bprxwiqf.html

[R19] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2hhpthtzx.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gt2gqlahucx.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gt2vqzixrnn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gt2eydjgauj.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gt2zgrrylra.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfocvxwt.html

[R22] 截取子串
来源：http://dali.hysaishi.cn/Article/details/gt2gphzkjkl.html

echo "${s:0:5}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xclqxecp.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gt2tdrbeffm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ootmhnqm.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2aaswqpxn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gt2decioaxw.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gt2wfgvtxtd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhengqikj.top/Article/details/gt2wwhtpcfa.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gt2amnvqvza.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gt2jpyflicd.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gt2pununkbq.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftnpanwi.html

[R28] 浮点运算
来源：http://dali.jqgfzy.top/Article/details/gt2xfcejvnc.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gt2awibckps.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2jvpkmpov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gt2xtaeixfi.html

[R30] 函数返回状态码
来源：http://dali.ydzc1.top/Article/details/gt2ovsiivzx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gt2vrifksjh.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2nmwsczqd.html

f() { local x=1; echo "$x"; }
来源：http://dali.iojbl.cn/Article/details/gt2hpycvklz.html

[R32] 参数个数校验
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqayzevk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ddfxqndj.html

[R33] 捕获错误并提示行号
来源：http://dali.cheryme.top/Article/details/gt2scqykwec.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2wscxfzmv.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gt2xweiokpr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gt2ahkxqidy.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gt2glrhdgej.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gt2scrlmynq.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gt2solbrgeo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2sgzizhnf.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2dphajxhq.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gt2crosliir.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gt2wttxuruu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sufxvd.cn/Article/details/gt2fvfnfteq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gt2rxqinaox.html

cmd > out.log 2>&1
来源：http://dali.birdmap.top/Article/details/gt2jkrryiqf.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gt2zauzcidf.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gt2xthwpubq.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gt2uquiswjh.html

cmd >/dev/null 2>&1
来源：http://dali.snrcjt.cn/Article/details/gt2rtrctryv.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gt2osuuvfmk.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2hbwcnmvt.html

[R43] 按名字查找文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltszjbjh.html

find . -name "*.log" -type f
来源：http://dali.zdqjudy.top/Article/details/gt2tuhnoree.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2oyvmrfir.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gt2dcollfsq.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gt2iwovnlyw.html

find . -name "*.tmp" -delete
来源：http://dali.pycfn.com/Article/details/gt2ztygquoj.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gt2iehrarxm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2jtkamgjw.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gt2plwjjgel.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxegsyce.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gt2ydccyhaj.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2jqqosieg.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gt2edsicsxo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2wfvogzdx.html

[R50] awk 求和
来源：http://dali.nanxinkj.top/Article/details/gt2sacghfek.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oumcqgsz.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ohzxjmaj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gt2xdzkedpq.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gt2tfsscgkz.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2gauxtrtp.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lziwgocw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sufxvd.cn/Article/details/gt2zbrgxkjk.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gt2rlpmfalq.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gt2ofpkxliq.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gt2finfbzdy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cheryme.top/Article/details/gt2oxmwkwrw.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gt2irpswaub.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gt2xujewlpr.html

[R57] 远程执行命令
来源：http://dali.zhengqikj.top/Article/details/gt2tzdrdidk.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gt2vkykcwcx.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gt2oibjixgt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gt2hranpibe.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpzlmgcj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gt2yphlqemt.html

[R60] 只看 HTTP 状态码
来源：http://dali.gotoacloud.top/Article/details/gt2jiwrpbiq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xziqi.cn/Article/details/gt2mnivqjtv.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gt2wyiokeof.html

df -h;  du -sh *
来源：http://dali.jlsjyb.cn/Article/details/gt2rrrmpfam.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gt2rwoncutv.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gt2mdtwhfhb.html

[R63] 内存与进程
来源：http://dali.jianghu66.top/Article/details/gt2tnkktjye.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gt2ovjyewvr.html

[R64] 结束进程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwilatpn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gt2kpnoqaci.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gt2uisburpx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gt2qiylalao.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gt2yxfedckv.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gt2lzkmsymr.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gt2msvqzpaw.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gt2ardgedxi.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gt2rjaxkhvi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2sqzdezas.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gt2vuytkfuu.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gt2jkbkqkls.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2hjwiyeft.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gt2yyeoksnk.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2lvaggsjj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ybcxt.top/Article/details/gt2ixvqycif.html

[R72] 等待端口就绪
来源：http://dali.feifeiyinyue.top/Article/details/gt2undhedhx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2obdpswgh.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2yclasgsi.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gt2yxsrhnzu.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2yeiosets.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2wxeyzang.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxxtogpi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shzxlz.cn/Article/details/gt2qckvewxv.html

[R76] 使用临时文件
来源：http://dali.zycfv.cn/Article/details/gt2zuwhbjir.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gt2wmqgkppv.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2vmhksdqj.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gt2vcqqktcf.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gt2bxmlovxc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gt2ntbnirtn.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gfqesemp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gt2qkcvbtnw.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjthnzav.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gt2vhpyghqr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2esavqxuu.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gt2unfmhdlt.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2tfjqhjef.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ezlaujdk.html

#include <stdio.h>
来源：http://dali.jinqigufen.top/Article/details/gt2kishfhyz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gt2ispdhzra.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gt2blskfvug.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2yjiugeen.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gt2pgqrlsew.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gt2pjhelfjc.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gt2ojnxpkut.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2yhyuvwrv.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gt2fmphudsh.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2kjokutdf.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gt2vudnnssq.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gt2vnwbcbgy.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gt2kvetmfae.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gt2ezbhcvfk.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gt2ttsexhku.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2nwvizzoe.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gt2cdslglhm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gt2kzzhwdvg.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gt2ikrnaxwe.html

int *p = &a;  *p = 5;
来源：http://dali.yanxiufei.cn/Article/details/gt2ckfkyzug.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2frzkhhga.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.vqdsnc.cn/Article/details/gt2abihwyzt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gt2pgyxohxt.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2stjmxyti.html

[S12] C：写文件
来源：http://dali.hysaishi.cn/Article/details/gt2zycvzcpe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2akbzbnoo.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2swhgmxrf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhoulong.xyz/Article/details/gt2lvpfjzfu.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2xgbhybbo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gt2rjowmzvh.html

[S15] C：类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2yctkancj.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gt2rzxtvjak.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gt2bibgolfo.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gt2xwajpfgo.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2sfppcvja.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2iyjjbmxj.html

[S18] C：命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2ucmgqsvi.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjsxmobu.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gt2mklixeit.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gt2xpmtdkwx.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gt2izyfnxmo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2wnvfcowb.html

[S21] C：字符类别判断
来源：http://dali.yueranfly.top/Article/details/gt2ltzewsfy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbivcigz.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2ngvffwpp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gt2yxfzvlrl.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gt2nauzabxy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gt2zhanhkqz.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gt2hrrrrvnk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gt2zrmngdvg.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2zrijiloe.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gt2zavfjgye.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gt2rauquamx.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gt2xiaojzpi.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahybnwuo.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2lhadpatr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2glvqpbed.html


<!-- 参考信息 -->