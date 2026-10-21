代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtfugqqpjv.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtzucprpfb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtmybjyfwb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqfdkrjja.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtllkdothl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyderzxf.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtrteupasc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gttctznqgb.html

[Q63] 开启事务
来源：http://dali.yanxiufei.cn/Article/details/gtwumqmqpc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtrvvryttp.html

[Q64] 提交事务
来源：http://dali.redwolf501.top/Article/details/gtwyjhcrgx.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gttzcsiuye.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtdbzhxflh.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtdrxqpiah.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxhlpyul.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtwcqveswk.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gtcdxxtypc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtwgodlwpl.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtwmrrbdbw.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtvkyjutvk.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtejuwpdsw.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtupmmnvrg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtufjttagk.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtehwrsphl.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gttuyqywyz.html

[Q71] 查看建表语句
来源：http://dali.yuanzhike.top/Article/details/gtzelfcmtd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtaptftenb.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtoynvwnxz.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtptrroqxe.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtxwhsqkxt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtpkqpardh.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtwaivlpiw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gtygfcsqoi.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtgrzfdsri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtmocsoaba.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtozwwmhhg.html

[Q76] 按天统计
来源：http://dali.feifeiyinyue.top/Article/details/gtzweameig.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtejihqzai.html

[Q77] 时间加减
来源：http://dali.jqgufenzy.top/Article/details/gtkurnrgkc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gtdbnevmdf.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtktuksman.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gtbvjqfwum.html

[Q79] 字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtewxldwpi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guannengcc.top/Article/details/gtcqstooxw.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtzenshlnt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtxouocqgh.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtkmhcenzj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtpqgqoqyz.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtqqmwwryo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyophpdxt.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtqxvocpcz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtrddxhozi.html

[Q84] 去除首尾空格
来源：http://dali.yj202588.top/Article/details/gthsghipcc.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtnazgyfxx.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdejquina.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtnpfdsclo.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gttakunmli.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtgjjjlkxt.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtjmaowdxr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtssfnizjn.html

[Q88] 行转列（条件聚合）
来源：http://dali.aibaodan.cn/Article/details/gtichllvfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gtmfpjkrjk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtrvurjdug.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtothutakv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtoyljfqrn.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gtypbekpzy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtqdveednz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtekdsdaoh.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtatvhonva.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcmdeswcy.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gtpdauyixk.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtsnrwtpbr.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gtnvdxikfo.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gtquyyafsv.html

name="Tom"; echo "$name"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsqjjsyo.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gtjtsfcibb.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gtjlqubleg.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtqxhhxfjo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtedfsvpfa.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtovumwlre.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtwkwxjcgh.html

[R06] 判断命令是否存在
来源：http://dali.gzhubu.top/Article/details/gtpyenanyg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nwbrower.top/Article/details/gtdguzxkmo.html

[R07] if 判断文件
来源：http://dali.chenzaomai.com/Article/details/gtewnivinv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gttlkasszi.html

[R08] 数值比较
来源：http://dali.iojbl.cn/Article/details/gtpbmztgmo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtuasuiojz.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtrbnbqszh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtjikvlvgl.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtbkfwwnse.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtnpsjhzds.html

[R11] case 多分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqewdrdh.html

case "$1" in
来源：http://dali.316326.xyz/Article/details/gtlegoylsc.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrmfnpes.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtplbrndvg.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtczwtbqnk.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtxvmhemvm.html

[R12] for 遍历文件
来源：http://dali.iojbl.cn/Article/details/gtufmrdbxf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cheryme.top/Article/details/gtohuyzidq.html

[R13] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtocbsnjdh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtvtgykaay.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrbdxlxu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtxwxfbstw.html

[R15] while 逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtiebeedcf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuanzx.com/Article/details/gtwcewlxze.html

[R16] until 等待条件
来源：http://dali.birdmap.top/Article/details/gtopysknna.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtqctnmjtn.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtljugtnpo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtugquhpot.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtvqtwuswp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gtchkpxqou.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtuoqeqlcl.html

echo "${#arr[@]}"
来源：http://dali.tianlin.xyz/Article/details/gtsnfwpkmn.html

[R20] 关联数组（字典）
来源：http://dali.nwbrower.top/Article/details/gtqvsjusbu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gtmwbqcasb.html

[R21] 字符串长度
来源：http://dali.xuetiantiany.cn/Article/details/gtsegbjepr.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtlmkjydgo.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtpchbvsfa.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtyxjoksmx.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtjfjoyglz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtrkhdxbrs.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtgbvisumx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtoxbrmzvu.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtywbufbtq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gogol.net.cn/Article/details/gtftrvijqv.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcysnroi.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtncpusiad.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtihomclur.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtsopbqlhy.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtoudgqdrs.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gthoeulvjl.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtuxpujrth.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtfjpfjlfn.html

[R30] 函数返回状态码
来源：http://dali.xziqi.cn/Article/details/gtzjmftgkk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkoowksc.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoaayjhd.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtvaogbrsv.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtimqzckvu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtreojmjip.html

[R33] 捕获错误并提示行号
来源：http://dali.guowangkeji.top/Article/details/gtxaqtoeat.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtqdzfoitf.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtakxllxsu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtneyuzutb.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gthtyrrgfs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hywenlv.cn/Article/details/gtkjsvwgxb.html

[R36] 并发执行多个任务
来源：http://dali.daxiang520.top/Article/details/gttooluhln.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aibaodan.cn/Article/details/gtxynmgbfd.html

[R37] 把输出赋给变量
来源：http://dali.xinyue.icu/Article/details/gtijdqppwq.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtmkofjefz.html

[R38] 管道串联
来源：http://dali.ppjwa.cn/Article/details/gtdgfolbos.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gtpgvredtl.html

[R39] 重定向标准输出与错误
来源：http://dali.yueranfly.top/Article/details/gtxtwlxtms.html

cmd > out.log 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtleytrjuh.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gtowyjzixn.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtweupwcoy.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtbzsknzzw.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtnyehfnvt.html

[R42] 输入重定向
来源：http://dali.cashguo.top/Article/details/gtbjjmlopv.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtbpgkgigg.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gtzscforzm.html

find . -name "*.log" -type f
来源：http://dali.yueranfly.top/Article/details/gtazegicuy.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gtlazcutyz.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gtdzlscowo.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtsjcvhvvx.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtzdhhoagk.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gtfxteaisp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtsrdwxgcp.html

[R47] sed 单行替换
来源：http://dali.pengpengdd.cyou/Article/details/gtzulfclqu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gttuqvnxwn.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gtjttsdkgx.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtjoowjqcs.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtwrvfdqql.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtoafitpbb.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtvvpcsahf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtvomtvcjd.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gtxikurdhu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtvdjxbizg.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtyorjfwpm.html

wc -l a.txt
来源：http://dali.guannengcc.top/Article/details/gtletvmmxp.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gtmkxwmmwj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtydmynovx.html

[R54] 比较两个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtngdjvsem.html

diff a.txt b.txt
来源：http://dali.kuanghao11.cn/Article/details/gtkfdqbgfo.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gtcdjchnyh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.quarkkingdee.top/Article/details/gtzqkvevcu.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtckhhoxcg.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtyemetphh.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gtisvwespd.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtwfxurjxz.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gtatiyjvbm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtwmdijwbe.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtkgmugxde.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtwbbbygzr.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtquwqnwox.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtmmvimcxh.html

[R61] 磁盘占用
来源：http://dali.tianlin.xyz/Article/details/gtczusveob.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gthndjthal.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtoganproh.html

du -ah . | sort -rh | head -10
来源：http://dali.yuanzhike.top/Article/details/gtrdatngsc.html

[R63] 内存与进程
来源：http://dali.sufxvd.cn/Article/details/gteifpuwod.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtrotjlvjp.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtyzhfcnbh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtouqtxytg.html

[R65] 查看端口占用
来源：http://dali.gaohongyu789.top/Article/details/gtmmrpiiuy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gtkttjleiz.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtcjikwmxk.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gtnqmzbdbi.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtiqonqugn.html

openssl rand -hex 16
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamfifzbi.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtkpqcasic.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtdivhbhbj.html

[R69] 生成随机密码
来源：http://dali.ydzc1.top/Article/details/gtcqabjaer.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtiwztlrsn.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtuppjzcwh.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtlnbikdit.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqphhdagq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtyvyrtfpi.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtrxbmkueg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvtptlnn.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtnbwhhkmi.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtxcvyjhxu.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtyzzjffxq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtdpyiznxg.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gtvvhwzssc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xinyue.icu/Article/details/gthbhfyukq.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtlwbkazad.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtwzoygtlz.html

[R77] 读取用户输入
来源：http://dali.fengsongda.top/Article/details/gtwaqueuvv.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtzjwbymiw.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtgxjdkgbg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtnytpxevv.html

[R79] 解析命令行选项
来源：http://dali.aizwys.cn/Article/details/gtkyecyyfa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtqsogzxis.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtjsyxfhuk.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtufmknbfb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnvwdmmkf.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtpiycnrfr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtqtxcrceb.html

[S01] C：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnijaheto.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gthmpntytu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.c1oappe.top/Article/details/gtsmgtlbmk.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258888.top/Article/details/gtcmqkmmya.html

int a = 10; printf("%d\n", a);
来源：http://dali.dianchejie.cn/Article/details/gtmvbotfgj.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtcthsgsjn.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtkjixypon.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtfjlykodh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.smart0.xyz/Article/details/gtdgysqjji.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtallsqmye.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtsvgrrezu.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gthyahzdem.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcztcnqiq.html

[S07] C：数组遍历求和
来源：http://dali.guannengcc.top/Article/details/gtxsdwadsi.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gttcplujtp.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtrvudngrg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gtebdtzhpp.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtmiechwpi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtkumqexvt.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtrdcjzlor.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqarxadx.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtqdmtusht.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtclugvbti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtsorqxbbv.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtyjlcpbsx.html

[S12] C：写文件
来源：http://dali.jiagoushi.top/Article/details/gttybrihhk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gttrqcyfjg.html

[S13] C：宏定义
来源：http://dali.wangdashe.top/Article/details/gtshptnzwh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtysywiatq.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtmdudonbc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtqkixfbqq.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gttzsqnxrw.html

(double) a / b
来源：http://dali.zdqjudy.top/Article/details/gtojjqdgcw.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcykmvru.html

x |= (1 << 3);
来源：http://dali.haohaochexian.top/Article/details/gtbcgisuyx.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtetxxcwof.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqzckuxv.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtbreaygqc.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtrwujowuz.html

[S19] C：快速排序
来源：http://dali.zdqjudy.top/Article/details/gtsqgzfrrz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtqehkmopg.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtfjlopkcf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtjxqhvykd.html

[S21] C：字符类别判断
来源：http://dali.jqgufenzy.top/Article/details/gtldsaopri.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.feifeiyinyue.top/Article/details/gtaqxepzjj.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtnyhgxhnb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dianchejie.cn/Article/details/gtitkiafjo.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gttobroznv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ivvv.top/Article/details/gtryhuzajb.html

[S24] C：获取本地时间
来源：http://dali.birdmap.top/Article/details/gteberyhiu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtyqhlfbuv.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtcscysdla.html

memcpy(dst, src, n);
来源：http://dali.snrcjt.cn/Article/details/gttoepcbcj.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtbyhttmdu.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtcbtysnzd.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtjdedlnlz.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfsthgms.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtyyhmjdiv.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gtuiwvzqlp.html

[S29] C：变参函数
来源：http://dali.wangdashe.top/Article/details/gtzqjuznku.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtrknokhzq.html

[S30] C：头文件保护
来源：http://dali.aibaodan.cn/Article/details/gtaxlvytze.html


<!-- 参考信息 -->