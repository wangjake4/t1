代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gttezmkocc.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtbspgwubu.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtsuiazxqj.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtxgovbenp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtlctcgjyk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpodvxmbv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtrudxmupk.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtpvchodxc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtstqurazl.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtnlqvenyx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtqncjiyll.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gthoxumiuu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtnyajcmca.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtudqjfnxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.andypj.xyz/Article/details/gtxlxygoui.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwscxrypp.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtpizxxpif.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtvzjtsnbb.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtlruaahyb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gtiohbrvac.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtrfavvvjw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtsmqsalho.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtjseavtxp.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtdxbhhexm.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtyvqxnpkz.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtsarxczji.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gtrmuvxpvn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtetodlqky.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtscotsgtt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtaolmulvb.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtukihnbsh.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gthgvaownl.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gthxzbjtnj.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtqjtqwsqr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtazstrxlv.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtsagcvutj.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtfjjkkpyo.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtmkovkmyi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtqujtivnf.html

[Q72] 查看索引
来源：http://dali.zhongyouzk.top/Article/details/gtosskimyv.html

SHOW INDEX FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtcxpsdwyd.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtnjbvrxui.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtsypxznlo.html

[Q74] 强制使用索引
来源：http://dali.jianghu66.top/Article/details/gtoqlulvnx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtbozpeyyh.html

[Q75] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtzaupddus.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtkrrpauik.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtsubpxtau.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtuiwpthpk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtnamlaary.html

[Q77] 时间加减
来源：http://dali.hysaishi.cn/Article/details/gtczroparw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtmbaqnejv.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gtdluvxipg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtpzqtxraw.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtinbwpvxg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtasosyngr.html

[Q80] 字符串截取
来源：http://dali.haohaochexian.top/Article/details/gtwgofqogk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxfetqiup.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtnsrjbnqp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbocswep.html

[Q82] 字符长度与字节长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxaoiimz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtsjafpzar.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtkbjmpzna.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtlgceghxy.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gthtmiwahe.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtrnppzejy.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtayfjjtqo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gtmpvgdkum.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gtbibqngnz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtfgyducog.html

[Q87] JSON 字段做条件
来源：http://dali.hnqzz.top/Article/details/gtcrslmjwk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtbjvfylig.html

[Q88] 行转列（条件聚合）
来源：http://dali.snrcjt.cn/Article/details/gtcufdaqcz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pycfn.com/Article/details/gtjkekfubs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gtitvlsihv.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtxsxlhmmx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtflabovhb.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtuixezqem.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gzhubu.top/Article/details/gtwibpqpgf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtwsxwhopi.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtwspmxlre.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtsrhaiajb.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gthxpbmiuf.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtokgowexa.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtymbxhlxl.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gtxjlsmqwz.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtfkbucxzq.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtfgnygnwl.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtbggexags.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gtbrwuuxnu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.bjfxy.top/Article/details/gtulorjuwl.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gteyhlrlbc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gtcldxwffs.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxxtbhsf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtnpsthbjx.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteedjtfhd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gzhubu.top/Article/details/gttfcbrqvb.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtghzjsjpd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tanke756.top/Article/details/gtetsfvxbc.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtxgmwlbml.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtlgwjymdg.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtygegsxba.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cashguo.top/Article/details/gteoovwhtb.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtgwfbcapo.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtxwozuaav.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtqioawyzk.html

stop)  echo "停止" ;;
来源：http://dali.aizwys.cn/Article/details/gtxdotsrhg.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtvzpjssmt.html

esac
来源：http://dali.cqqwz.cn/Article/details/gttmakenem.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gtwujfsyas.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtmantjodg.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtkpeldlyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtxvteihaa.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtawsbclrq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nwbrower.top/Article/details/gtfzgorldn.html

[R15] while 逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtudcgjrbt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtmlidpyra.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtfratsvpj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtrzkaviac.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gthqtbrusf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhiwuduotai.top/Article/details/gtppxxgkmy.html

[R18] 遍历数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsnjjzwd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gtzvaypcww.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtjtfvkazz.html

echo "${#arr[@]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtepyediju.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbrfttabj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shuidangran.top/Article/details/gtwjmiklbr.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtremgbwlr.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtaizlueyh.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyoumjums.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gtivtxkcdq.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtsixdaccb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gtnwlcencp.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtspqwfmdf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtklpbfxvz.html

[R25] 去后缀 / 去前缀
来源：http://dali.jiagoushi.top/Article/details/gthqzxpmqp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gtfnfpowfq.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtemcfbcyu.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtzkmbjpff.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtemexucfu.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gturdtaaah.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtuwhilgzt.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtmpsilczr.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfwvwduf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtnjcieeeg.html

[R30] 函数返回状态码
来源：http://dali.jqgufenzy.top/Article/details/gtkkeygpxf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtrngdxict.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gtxsokcuir.html

f() { local x=1; echo "$x"; }
来源：http://dali.gzhubu.top/Article/details/gtgbjrfqtp.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtfqituoxz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtcnuvuzwt.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gtvvpzprpo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cqqwz.cn/Article/details/gtxohnkgsi.html

[R34] 退出时清理
来源：http://dali.nwbrower.top/Article/details/gtkicrcilu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtnlajpeyl.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtbartitih.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gtfpqolbbq.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gtdyroyppn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tian-w.cn/Article/details/gtycopvtru.html

[R37] 把输出赋给变量
来源：http://dali.ivvv.top/Article/details/gtjrhmlffw.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtsjesluyg.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtsopfwgpn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gtsefxbuuw.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtqeogikpl.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtmpwcxsom.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtrkuzadxa.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtulonsbts.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtcivoqrbf.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtuwvtysfw.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtoyreltep.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtqtmnhfvt.html

[R43] 按名字查找文件
来源：http://dali.quarkkingdee.top/Article/details/gtzdvhggyz.html

find . -name "*.log" -type f
来源：http://dali.svipenyu.cn/Article/details/gtdadamdwn.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtalyhbnvl.html

find . -mtime -7 -type f
来源：http://dali.bjfxy.top/Article/details/gtwzpaosxm.html

[R45] 批量删除
来源：http://dali.yangfankeji.com/Article/details/gtptjczcan.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtctrckxbq.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtikveenpe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtcehewvsy.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtpttvowzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gtveihcfcv.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtteykiihx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkzmwvye.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtfcecctam.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gtvxoewddx.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtkraqbblm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtzqesashn.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtlmkinzab.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtrgtdlvwx.html

[R52] 统计行数
来源：http://dali.jlsjyb.cn/Article/details/gtvbztryhw.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtmgtxfhpm.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtrvuepsjg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtssdlrjda.html

[R54] 比较两个文件
来源：http://dali.mhx1999.top/Article/details/gtohhaglae.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gtoeurysuw.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtwabisnzp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gtzlabwfsl.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtdwjrbcax.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gtuymqpjld.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gttwhxhcon.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtbnsvilcf.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gtzbrkyxdb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtpzkwxlvn.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtkpblpijl.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtcvwjtvdo.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtnvygvqrb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtxphujzty.html

[R61] 磁盘占用
来源：http://dali.mhx1999.top/Article/details/gtblssbbyb.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtkukmcepj.html

[R62] 找最占空间的文件
来源：http://dali.nanxuanxn.top/Article/details/gtcebntaig.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtaubfbdbd.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtquwfdebl.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtqcwcyouq.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtrpxyuouk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtivibgdeg.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gttauglvua.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtvksfxkuf.html

[R66] 定时任务
来源：http://dali.hammf.cn/Article/details/gtffqjwzoa.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gttoeoikxh.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtwqqlzrpb.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtcaxrjrwr.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtwdatmabv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtoolelgum.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtanxexxby.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtpxbxvltf.html

[R70] 时间戳与互转
来源：http://dali.nwbrower.top/Article/details/gtmywjskad.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtvizgtjno.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtwjrsnpln.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtkakuglxv.html

[R72] 等待端口就绪
来源：http://dali.yuanzhike.top/Article/details/gtbhsygfjr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gttsoalwhf.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtntvpiutz.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtwpkrvdlw.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtdlmbhdru.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgfovpws.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gtmfcvpmmr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gtphruwumx.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gthermxzbp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gturkntszn.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtaegqhbcp.html

read -rp "请输入: " ans
来源：http://dali.shzxlz.cn/Article/details/gtnzqbtjwp.html

[R78] 交互式菜单
来源：http://dali.snrcjt.cn/Article/details/gtyrlegjgf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gtibgnappt.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtlqrxcqgh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtfbwgscfx.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtidsetjjr.html

time ./run.sh
来源：http://dali.svipenyu.cn/Article/details/gtthclrzbh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpfgpnuvu.html

S. C / C++ 专题
来源：http://dali.hammf.cn/Article/details/gtxfhqzaqy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfdqkdfdn.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtmyrefsvy.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtlcjjdzvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gtrxhwdkny.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtqnoqrxyg.html

int a = 10; printf("%d\n", a);
来源：http://dali.nwbrower.top/Article/details/gtvqfhqyua.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutevcbgh.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtekyjlurh.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtdxrrziwr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtxnsggqvx.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gthnuzaaer.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtrbtwutft.html

[S06] C：字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtfhcrtdlx.html

strcmp(a, b) == 0
来源：http://dali.jinqigufen.top/Article/details/gtgcaanaey.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtzsbfhvgl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtbdspazeq.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtkmggkpgz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtcegydvad.html

[S09] C：结构体定义与初始化
来源：http://dali.tanke756.top/Article/details/gtlfqomxwb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xinyue.icu/Article/details/gtutdtauuf.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtjpkvzsdk.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtfivwqwrc.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtlpiwifmz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtdsktmzgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtlgxrdrxj.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtqwqggx.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtfnjvzeym.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtfuxawcxi.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gtfbhyiqre.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gtwolacfnb.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtfkoimwzs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtnbaqsjea.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdieebnfd.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtdjackfvd.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtuspjlwxf.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtykltfwiy.html

[S17] C：安全拼接字符串
来源：http://dali.yongpay.top/Article/details/gttwljwqml.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqypysfm.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtnyvrbyuy.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtineerncs.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gttizbudjw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtodwywkxx.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtjmcsxfux.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtjojohpxu.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gttubdciis.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gthgmdoflp.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtlmgoydcu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnaaemxn.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtjnfzqpvh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtsqxruiqm.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtedfyrxnz.html


<!-- 参考信息 -->