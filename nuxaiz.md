代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtvkvsfxeh.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtcfrkugwz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtpuafkauu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtbikvtydx.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtnmolkkmk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmkrgbtyv.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtwrpndqys.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtpnjfjujf.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtfdrxlqfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gtdgajevdr.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gtqwdirjlw.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtfxuunyvs.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtatkbgflu.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtjvuiylat.html

[Q66] 行锁查询
来源：http://dali.jqgufenzy.top/Article/details/gtsxtsyuld.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj202588.top/Article/details/gtjwrcitbw.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gtstarxglm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtjvlzylca.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtpaxhaztm.html

SAVEPOINT sp1;
来源：http://dali.yongpay.top/Article/details/gtsxgeaied.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtnikjkoms.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtnishlnjn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtoygpupwy.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtezwocpwb.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gtilolugjk.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtgldqpnun.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.kuanghao11.cn/Article/details/gtjbuycokf.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtywkqrggk.html

SHOW INDEX FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtjtfifdbi.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtsejtnylr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjvnngtv.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtgmhswwuo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtqwbhrxmp.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtfpzmtbwd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtnjfwokuo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtzvhlhuhy.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtrypabppm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtshpewcts.html

[Q77] 时间加减
来源：http://dali.xuanzx.com/Article/details/gtlqcdctss.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.quarkkingdee.top/Article/details/gtmofaskrq.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtkwlkblel.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yvedp.cn/Article/details/gtbdnlaxel.html

[Q79] 字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtngywzkcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtlcldjnwd.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gtryreayec.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtonermlyu.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlywqprey.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtlrqyzect.html

[Q82] 字符长度与字节长度
来源：http://dali.dashuyun.cn/Article/details/gtwyvwbnlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtzzgydljl.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtkgqyuxau.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtfgkuztpi.html

[Q84] 去除首尾空格
来源：http://dali.feifeiyinyue.top/Article/details/gtcymevsbn.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtufjczsdo.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gthsamabex.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtvzktewfb.html

[Q86] 读取 JSON 字段
来源：http://dali.feifeiyinyue.top/Article/details/gtgqxbvfgj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtfecruwla.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtytvfnxvs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtjmnwahgk.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangshuangyany.cn/Article/details/gtejnejixu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtgfijaqls.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtietrvznc.html

[Q89] 判断表是否存在
来源：http://dali.hammf.cn/Article/details/gtbnzqedma.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtdbwawdtu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtdtgjiqnf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtvfknphde.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkpjgyhzp.html

R. Bash 专题
来源：http://dali.zhixingplan.top/Article/details/gtuxbjebgx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtubtidybl.html

[R01] shebang 与严格模式
来源：http://dali.redwolf501.top/Article/details/gtahrgruvt.html

#!/usr/bin/env bash
来源：http://dali.zhixingplan.top/Article/details/gtuytxcoti.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrnlnlxc.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtgtiqyiwq.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gtwrqimhde.html

[R03] 只读变量
来源：http://dali.sxryk.cn/Article/details/gtdershwbl.html

readonly PI=3.14
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyjkcask.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoqsnsiu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtpxityxyb.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtnewhwpxf.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtddlvkxsx.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtoocvxiwy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gttoscpqfe.html

[R07] if 判断文件
来源：http://dali.9152youxi.cn/Article/details/gtaglqfwyh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtjuqfoprw.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtsefmrpng.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtmfbbugjr.html

[R09] 字符串比较
来源：http://dali.havefunace.top/Article/details/gtmwluxayp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ppjwa.cn/Article/details/gtlhaimvlj.html

[R10] 正则匹配
来源：http://dali.yanxiufei.cn/Article/details/gtmpawckkk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtthbyhsax.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtwmxerdki.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtdacoaokb.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtbtnrihjm.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtjqnuvoou.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtzrmgddbw.html

esac
来源：http://dali.ybcxt.top/Article/details/gtdqmjuyzp.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtqgibtanc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.vqdsnc.cn/Article/details/gtqqjuabop.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtvbxlsgme.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtcfdttsvc.html

[R14] C 风格 for
来源：http://dali.zhixingplan.top/Article/details/gtygluiuig.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gthzeuqjpz.html

[R15] while 逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtmdhwwogg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gtsgvpsgmr.html

[R16] until 等待条件
来源：http://dali.sysykeji.top/Article/details/gtncdatyjj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtxdxqysnq.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtscmuhlax.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.316326.xyz/Article/details/gtjmdjgbvw.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtjqdmpedx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtafbnzwoi.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtsillkbjj.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtefrdzoau.html

[R20] 关联数组（字典）
来源：http://dali.sweek.top/Article/details/gtvykzqjly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtzhcsslfd.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtjsbtmafj.html

echo "${#s}"
来源：http://dali.daria6918.cn/Article/details/gtmfwyopln.html

[R22] 截取子串
来源：http://dali.feifeiyinyue.top/Article/details/gtzvzsfhxa.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuoviscu.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtkqjbslnf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yonumen.top/Article/details/gtmqhwihqm.html

[R24] 大小写转换
来源：http://dali.ivvv.top/Article/details/gtxjqbcmbr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtxndfqxgu.html

[R25] 去后缀 / 去前缀
来源：http://dali.aizwys.cn/Article/details/gtyksiqqah.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtlsgqzhtb.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtrfarinap.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gtxkksglkp.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gtudcfsstu.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gttvkoqves.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gtgvpsnyry.html

echo "scale=2; 10/3" | bc
来源：http://dali.jlsjyb.cn/Article/details/gtumcoqyjh.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtwrejbmae.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ybcxt.top/Article/details/gtvxcfawbs.html

[R30] 函数返回状态码
来源：http://dali.sweek.top/Article/details/gtdbpkvvgm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtnwgdyntv.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtwwzlakez.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtbpgxndbk.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtlvndfezl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtjodmgovw.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtpldocbsi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtllvxoqvj.html

[R34] 退出时清理
来源：http://dali.zhongyouzk.top/Article/details/gtvtbbsaqv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtowbmrmes.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtgzvbxgqj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtzdfmbjdt.html

[R36] 并发执行多个任务
来源：http://dali.dashuyun.cn/Article/details/gthpviwhhd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtnpazzggh.html

[R37] 把输出赋给变量
来源：http://dali.cashguo.top/Article/details/gtioeneonp.html

files=$(ls -1)
来源：http://dali.cdnleiting.top/Article/details/gtsfasnyxv.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtgojeaxxk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtjawgzlpq.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gtekcnuvco.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtoyuhwbzt.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtkvdesuuz.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtmpiduxib.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtlgcskgax.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gtdyfrjxiq.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtvsgtlqjy.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gteudzkbma.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gtzlheetrz.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtzbavlqkz.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtnbmustgm.html

find . -mtime -7 -type f
来源：http://dali.zhixingplan.top/Article/details/gtfxoptocp.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtldetmcod.html

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtefmjcygi.html

[R46] 递归替换文件内容
来源：http://dali.bjfxy.top/Article/details/gtkwbrmaxy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsonwzcfr.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtahngdwwk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtigrtjbau.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtbvksdoes.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwyrjbtr.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtfthrqowz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sufxvd.cn/Article/details/gtmnrkxmtz.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtmxoruhok.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgftxvmyz.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gtyqfjlbhd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.redwolf501.top/Article/details/gtphnngfcf.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gtqfollouc.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtshrbpsqp.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gttuyvgqtz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fzhhl.top/Article/details/gtetfgrbkh.html

[R54] 比较两个文件
来源：http://dali.hnxiangtu.top/Article/details/gtmngxbbzx.html

diff a.txt b.txt
来源：http://dali.sysykeji.top/Article/details/gtustfiywi.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtlqndcnee.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtckjzgllx.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gttcaovjgq.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtrcfsjubo.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtkjyxoxrm.html

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gtcxeczdmg.html

[R58] 下载文件
来源：http://dali.ivvv.top/Article/details/gtlmarhkkv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtcxghknvk.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtcsfssklb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtxevpkkwy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gtxghjmisv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dianchejie.cn/Article/details/gtqollqnkp.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtskexirwl.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtoltidxzn.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtdnokucrj.html

du -ah . | sort -rh | head -10
来源：http://dali.jianghu66.top/Article/details/gtzvbzdqtl.html

[R63] 内存与进程
来源：http://dali.daria6918.cn/Article/details/gtghpcebgy.html

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gtmjxzvzrf.html

[R64] 结束进程
来源：http://dali.cdnleiting.top/Article/details/gtvgbnebrb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.birdmap.top/Article/details/gtryqxbvha.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtccdgbiqz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtczlgvrke.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtzezugmau.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtnstuzihi.html

[R67] 生成随机十六进制串
来源：http://dali.cashguo.top/Article/details/gtujeaacfq.html

openssl rand -hex 16
来源：http://dali.tianlin.xyz/Article/details/gtbhxnpupo.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoubtsjq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtehxxpyib.html

[R69] 生成随机密码
来源：http://dali.jiagoushi.top/Article/details/gtlxsazanc.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtnkqnrwaz.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtoimdzvsc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtxqtrsutf.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtjkrdxoxa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gttnvmwpzt.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtprdfsbfg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtiebdetxo.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtifxdtnhe.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtlodmcycf.html

[R74] 批量重命名
来源：http://dali.yongpay.top/Article/details/gttgitiksl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtkrgxcbso.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtspcwsehh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenjidiqi.icu/Article/details/gtouzgmkzu.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtbxabzwhe.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtpmjcpibp.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtnucllkkv.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtfmdqvycx.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gterxipnwi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtsypzmdtp.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtumjpnfsf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtkxchutuw.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtbjfasupm.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtnfvhyjop.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzzgueftb.html

S. C / C++ 专题
来源：http://dali.iojbl.cn/Article/details/gtujvvwkov.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwuxjfxhx.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtyiavfsme.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gtdkkktftu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtzpubpjdn.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtwtoxciwb.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtgtehvrhi.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtjaxyvpli.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtvpyzaqsj.html

[S04] C：字符串复制
来源：http://dali.shuidangran.top/Article/details/gtcbdplrni.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yonumen.top/Article/details/gtqwseawoo.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtcnvhrijx.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtvvmghojn.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzeofhxg.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gttzmmojgl.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtqjtuzheg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.pycfn.com/Article/details/gtutxjulrt.html

[S08] C：动态内存分配与释放
来源：http://dali.daria6918.cn/Article/details/gtmzenwrhp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gtioaukhbd.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtayofziti.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.0kj1m.cn/Article/details/gtjwolgghr.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtdkdesloi.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtbbcnnnpg.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtsbkzxedc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtdmsfyxnc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gtiiuvivsb.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gtmvipflhp.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaofrifo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtemaeljip.html

[S13] C：宏定义
来源：http://dali.yj202588.top/Article/details/gtduulttsi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sysykeji.top/Article/details/gthmqmthxb.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtkymtpcze.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.snrcjt.cn/Article/details/gtngysvlrn.html

[S15] C：类型转换
来源：http://dali.meibo888.top/Article/details/gtvhmszgrx.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtbjlqborp.html

[S16] C：位操作置位
来源：http://dali.sweek.top/Article/details/gtjwhmcvub.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtbrcvbhcp.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gtdhgpseet.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtmouuyixd.html

[S18] C：命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtcuhdobrv.html

int main(int argc, char **argv)
来源：http://dali.smart0.xyz/Article/details/gtlojhmrnd.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtmcnlprvn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtebytnjtb.html

[S20] C：二分查找
来源：http://dali.yj20258888.top/Article/details/gtyrhelqbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtaccakiva.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtdrmoxcdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ehwqpu.com/Article/details/gtetmnocci.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gtyvamedtn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtnzmyofth.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtdswcfqfg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtyhrymnrn.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtlvqjrtfw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskqpfpnp.html

[S25] C：内存拷贝
来源：http://dali.hnqzz.top/Article/details/gtexpvolcq.html

memcpy(dst, src, n);
来源：http://dali.yuanzhike.top/Article/details/gtudbtmrdd.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtfvqgcbbi.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtfenqgain.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gthloldlyk.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtvwqiwesl.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtgazzuhyy.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtaxzxetgn.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtxvgypqah.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtaakopjbl.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtvblgpqps.html


<!-- 参考信息 -->