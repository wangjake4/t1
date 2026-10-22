代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gt2nutccent.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iysdimqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2petmclid.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxeumlpc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2xebzfiya.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gt2cuahnplc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gt2nqdgduft.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gt2kzbzrzad.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gt2jtdumjjz.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gt2bonlvtts.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gt2ddujojeq.html

[Q55] 排名（并列占位）
来源：http://dali.mhx1999.top/Article/details/gt2okrprvzh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.havefunace.top/Article/details/gt2zkbnuuge.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gt2swuogdsz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vlovhabv.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gt2dwxurwoi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrdgusev.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gt2xqndegkl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2ixuzihsu.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gt2pkuukyyc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2szitvftz.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gt2uprziujk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnhhdovh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2gxnyosji.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gt2vybxczah.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2giliscrd.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2iutvymou.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbfpgcbo.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gt2vcauqqwd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gt2tzpzpxvl.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gt2rzyuogtf.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzqewdjj.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gt2axfwweyy.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gt2iflsjxwx.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gt2yrjxighj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gt2bsunsktx.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gt2nhdnsuju.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gt2rwgjwmud.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gt2lrckdyjn.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gt2yqmedjxz.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gt2gqfzutxn.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gt2qbhwlqop.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2hhkinmiy.html

[Q70] 更新统计信息
来源：http://dali.jinqigufen.top/Article/details/gt2lfacfuxd.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwngfbrj.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myaudxyn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gt2ebdvplhp.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gt2mltupqdn.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2fgasvzrs.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gt2atdtqhhx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gt2cmcpkhwp.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gt2ijphqyqd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gt2wdoepdcr.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2fsbhuyra.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2rmlufavn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2kfaehfwn.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2ajovmkqt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gt2plthfzur.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gt2edfxtsgj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gt2yrhddozw.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gt2whxqtvik.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2qrpgowzf.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gt2qunpnwoz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gt2nsfwdbww.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gt2fykkjtxn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ubwmqgkp.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2hayejsge.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cheryme.top/Article/details/gt2gydlnyxr.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2enmyzywf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2vxekifat.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2ojkcveum.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2styigqtq.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gt2rzzzfwtl.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2wntiogej.html

[Q85] 数值取整
来源：http://dali.redwolf501.top/Article/details/gt2pdnmoxnh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2mkkqelen.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gt2ppeuaepn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gt2eazdijdl.html

[Q87] JSON 字段做条件
来源：http://dali.zhoulong.xyz/Article/details/gt2lotsxjwd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yuanzhike.top/Article/details/gt2tbhlpajm.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xjjwgnvj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gt2pqitejai.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2hvbrklxm.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzvfhmcb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gt2tflpsayg.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gt2jcaqtcow.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhixingplan.top/Article/details/gt2rwmefhas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jszflgow.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2opnnhsdv.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fwabmvlm.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gt2xfezsknr.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2uuweqymp.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gt2lqsgmoxw.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2kjwgbmvw.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tagdfxeq.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzmjlczh.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gt2jatyljbo.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gt2bxrnndbg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gt2mtckvzgc.html

[R05] 参数默认值
来源：http://dali.zhiwuduotai.top/Article/details/gt2tixluypv.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gt2ilatvvxl.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gt2rxloidbd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gt2qdenjmsf.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gt2fbquntxn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gt2ulcamxdi.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gt2xwfjlyjz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2nqhdnlgs.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gt2jkiujsxq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypgquwtx.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gt2oqgzzhai.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2nnpozbvl.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gt2azisnlub.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gt2jjjkjyxr.html

start) echo "启动" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gt2djxrrweu.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gt2tyvxhfiq.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gt2pqvdxewa.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2fxlwanpy.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfliyfcs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2shzbrnro.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbebpxxx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gt2fbfmfoxh.html

[R14] C 风格 for
来源：http://dali.yueranfly.top/Article/details/gt2nqlmqgsz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edpmkfvm.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2uvhsncnz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gt2oqretutz.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gt2yyhmqrnq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baatcrak.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gt2qvydpxsz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2mpgzqydl.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gt2bsvbketb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.andypj.xyz/Article/details/gt2clcwrppq.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2zzykilmq.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gt2wqknppwi.html

[R20] 关联数组（字典）
来源：http://dali.gaohongyu789.top/Article/details/gt2zdeswbds.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2imeuzowz.html

[R21] 字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2yoesnpqu.html

echo "${#s}"
来源：http://dali.bjfxy.top/Article/details/gt2bmbqeooi.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2obuzezsa.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jcfdaxih.html

[R23] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gt2gnaespko.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenzaomai.com/Article/details/gt2qtamwrgi.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2wtihpdpj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gt2yrjmylwy.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gt2tsripvvq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gt2qorgpzga.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gt2ofopndzg.html

now=$(date +%F); echo "$now"
来源：http://dali.xziqi.cn/Article/details/gt2mmgfiovi.html

[R27] 算术展开
来源：http://dali.sweek.top/Article/details/gt2orppcwpf.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymsjwoyh.html

[R28] 浮点运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rupuwtfh.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gt2pmtnfpku.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gt2oocvnerw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wyaifnhs.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gt2bpgljjfk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gt2pjeiqqqv.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncnmijni.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ewluuynz.html

[R32] 参数个数校验
来源：http://dali.jiagoushi.top/Article/details/gt2awkgvtex.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gt2csnnepzl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhongyouzk.top/Article/details/gt2gdjbngyw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gt2nmejocwg.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gt2rgblxvzw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2gyuvjvpa.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gt2nvllsvny.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gt2daxzsqjk.html

[R36] 并发执行多个任务
来源：http://dali.9152youxi.cn/Article/details/gt2otcadfrg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gt2rzsqjnyp.html

[R37] 把输出赋给变量
来源：http://dali.vqdsnc.cn/Article/details/gt2pmguzfku.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gt2kpdxxono.html

[R38] 管道串联
来源：http://dali.jianghu66.top/Article/details/gt2cateekag.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2bzfbwknb.html

[R39] 重定向标准输出与错误
来源：http://dali.xziqi.cn/Article/details/gt2xeofbnwr.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gt2xybdibol.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2yqoqpwsf.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gt2mgdxtssq.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gt2zaghiwtd.html

cmd >/dev/null 2>&1
来源：http://dali.cashguo.top/Article/details/gt2gusylvwe.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gt2bjppmoqn.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2wbjflgaf.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gt2eepnaaor.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gt2vonqkydz.html

[R44] 按修改时间查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhzjejox.html

find . -mtime -7 -type f
来源：http://dali.sufxvd.cn/Article/details/gt2kupjddww.html

[R45] 批量删除
来源：http://dali.0kj1m.cn/Article/details/gt2qcjxlcap.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kgggkctt.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lokjsfsr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gt2rbzruviw.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gt2ludmsvyx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gt2tqgflabl.html

[R48] awk 取指定列
来源：http://dali.aibaodan.cn/Article/details/gt2sheuquqr.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2czewhcer.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsyypekb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gt2qsxlllez.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gt2odiqcnid.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ybcxt.top/Article/details/gt2vkelcpvp.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gt2fvoubekc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cucudq.cn/Article/details/gt2xumhilqw.html

[R52] 统计行数
来源：http://dali.shuidangran.top/Article/details/gt2mscpgzrx.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gt2lkrmgmtq.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gt2koyuuiql.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gt2pfmyzyya.html

[R54] 比较两个文件
来源：http://dali.daria6918.cn/Article/details/gt2otlrwkxm.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbbiumjr.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggggeiku.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sazgmxeu.html

[R56] 远程拷贝
来源：http://dali.316326.xyz/Article/details/gt2qmjtcsvw.html

scp file user@host:/path/
来源：http://dali.redwolf501.top/Article/details/gt2yjoyzfbz.html

[R57] 远程执行命令
来源：http://dali.yj20258.top/Article/details/gt2vqdvquui.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gt2sxbwwvxh.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gt2eewqsizi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gt2yjutgupf.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gt2vxurquuk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gt2nzuxoddi.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2njcjknuc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gt2kjqicazo.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gt2bhuoampm.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gt2axqlcogu.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gt2cnruhsxh.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gt2sigqllhx.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gt2grqvilqy.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gt2dhqqzibo.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gt2jnkqewqc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxzredzc.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gt2wztoswtn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktqdbuzw.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gt2qrhvvkkk.html

crontab -e;  crontab -l
来源：http://dali.yj202588.top/Article/details/gt2psvetijr.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gt2cprzcqnr.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gt2gqgqvgnb.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gt2hivlfcmj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2hzbkfcac.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gt2gvczrejh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gt2sotcgfxz.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwdwdelq.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gt2dapijwcv.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2iqznemgb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gt2bipcwxnk.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gt2eockgbak.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2fmcizamw.html

[R73] 分割大日志
来源：http://dali.chenzaomai.com/Article/details/gt2gflwppbx.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqdqhras.html

[R74] 批量重命名
来源：http://dali.xziqi.cn/Article/details/gt2skrjtnyb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gt2fytbgyjf.html

[R75] 导出环境变量
来源：http://dali.yj202588.top/Article/details/gt2ufzynjyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gt2zfvhclvq.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gt2bpkomigm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2mchzdmjk.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gt2cvdqedvc.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2jmqgdzsg.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gt2zwgergvd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yanxiufei.cn/Article/details/gt2wgtvcqad.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gt2stxjcrgt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gt2rqieeqdk.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2xafbjygr.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gt2uzetvnkt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2awwlezhm.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gt2glqggwxi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xgklfdfz.html

[S01] C：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2mmxwzath.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gt2vuxxhrjn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gt2wdbyxlsk.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gt2cytgurgp.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gt2oiktaeuj.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gt2kzouumsp.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gt2crgiwbqu.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gt2gpktawoh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2zudfadsi.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2fimssisb.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gt2rnyyyhcg.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gt2cvljwxmu.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gt2uyoimvzx.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2npyopdsk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2zejbyijm.html

[S08] C：动态内存分配与释放
来源：http://dali.tian-w.cn/Article/details/gt2sjkipfwz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gt2mhizozht.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gt2xtbsumuy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gt2ubzzgpct.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjynyvnd.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gt2oiyfyqqj.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2wgcfejoj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gt2srerjtol.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gt2esmxybsg.html

fclose(f);
来源：http://dali.gzhubu.top/Article/details/gt2zvcfwuyu.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gt2qdcnyisf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2mdzwhgwq.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvlwnxge.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tian-w.cn/Article/details/gt2aaroudjm.html

[S14] C：枚举
来源：http://dali.nanxuanxn.top/Article/details/gt2wzzgxoys.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gt2hpebddgk.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gt2kcumajem.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gt2fpppifio.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gt2xyzblccd.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcgrsmzq.html

[S17] C：安全拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2lxdrdodt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.pycfn.com/Article/details/gt2incxjpyd.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2kzcrkfrc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2iatpqjfj.html

[S19] C：快速排序
来源：http://dali.xinyue.icu/Article/details/gt2cwkbwuir.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gt2zmzwwgue.html

[S20] C：二分查找
来源：http://dali.gzhubu.top/Article/details/gt2ixrpgqwa.html


<!-- 参考信息 -->