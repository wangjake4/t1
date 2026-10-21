代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvxeyxxsu.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoagjrqu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gthhkvehkv.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtbntplcpx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sweek.top/Article/details/gtuwspipty.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtiyklpgnj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gtplhosuqh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtxmtzntbe.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtflifpccl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjlkqhbm.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtoctymosi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtecldfaao.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gtvyrsruyz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gtjcgzqgsa.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtftplebjz.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtbwppjvuy.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtsndxkkol.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gtiptiwphh.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtjdqjfgki.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gtnqbrclun.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gtppcgzqfg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtizqakujz.html

[Q68] 保存点
来源：http://dali.zdqjudy.top/Article/details/gtpqmxmybu.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlndmvfy.html

ROLLBACK TO sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtfxpilybg.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtimysoolt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtjvgcugnu.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtkypemiev.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtmmaycksa.html

[Q71] 查看建表语句
来源：http://dali.shangyingyoupin.top/Article/details/gtwnxpvcgd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtndgqbbac.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtctjkocyh.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtmaoesrtl.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gtejeevzqm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gtikchyssu.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtslfubjhm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtnplienzk.html

[Q75] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtcludnuan.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehnvtfvs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtixeabfnr.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtdvpewvrt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.haohaochexian.top/Article/details/gtnntyudjo.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtsakfahsb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gttswkkaqx.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtfqajnesr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtwaejbkwm.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtkrpntjzt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gttwefimca.html

[Q80] 字符串截取
来源：http://dali.tanke756.top/Article/details/gtpbdexydb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtvusxfweo.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtdpijwhgd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj202588.top/Article/details/gtvovrfyon.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gtzbiwxahn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzbfjlrdx.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gtohosnfje.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlalkozoi.html

[Q84] 去除首尾空格
来源：http://dali.ydzc1.top/Article/details/gtuxmpbnya.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtxbdlnvod.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtafmzuorm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtetdgimps.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtptnvkbxg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtgbddlamx.html

[Q87] JSON 字段做条件
来源：http://dali.meibo888.top/Article/details/gttcvxzgaw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gtvriubsxv.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gthcyhfara.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtvajxuhik.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtbiypovki.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtdckuostq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtqzyyetjv.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtvpxfmgnm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtvacavhxn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmlrsdpkz.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtiiwaoldb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxjepwplw.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtuwhqgsze.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtsrzofddt.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtpqvrwdyk.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtvxmatwhw.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtndrckkck.html

[R03] 只读变量
来源：http://dali.mhx1999.top/Article/details/gtcpuujjfl.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gtvwldkqic.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtistgpkdp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtmmzaxgox.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtmciwdzsc.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtjfdmlrtv.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtnqkqwzum.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtolqfailq.html

[R07] if 判断文件
来源：http://dali.c1oappe.top/Article/details/gtbjufgslo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gttosdtijn.html

[R08] 数值比较
来源：http://dali.ehwqpu.com/Article/details/gtfoqcsvqo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gthymhjigk.html

[R09] 字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtsgetaivk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gtssiomfkw.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtoujycddr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtxfynrzsm.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gteuhwoaso.html

case "$1" in
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjtukpdcd.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtqtjwkxcg.html

stop)  echo "停止" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtidtykpfi.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtogmycluc.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdghmlao.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gtwqziiuje.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gtwdgxulmw.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtqtihxuuh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtuzsmjhtc.html

[R14] C 风格 for
来源：http://dali.meibo888.top/Article/details/gtlftsctgx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtqwvsfhfb.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtiezspgzc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ivvv.top/Article/details/gtssbwrtgt.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtkpqtgkdi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtliymdrgy.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gtyrjktcwx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gtvsffpkrv.html

[R18] 遍历数组
来源：http://dali.yvedp.cn/Article/details/gtbiidzrll.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtyndrwyvn.html

[R19] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtsbmfwbza.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtkvvjjkeg.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtyxtocfuh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtkuzkismq.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gtkamsdvqa.html

echo "${#s}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtigumlvfo.html

[R22] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gtusfaxoov.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtdonupgju.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtzunoxfrc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yueranfly.top/Article/details/gtigjoznst.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gtyjnsnnxz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yueranfly.top/Article/details/gtkykonlwk.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtycudciji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtzuggvnfq.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtcavbnuwa.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtegwwugez.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtwqochplk.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtxaksoqpx.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtwmlczmsm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmazfhpt.html

[R29] 定义函数
来源：http://dali.tanke756.top/Article/details/gtpdjimhlb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtmfkacdrf.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkdevsfd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtmbsjnfwo.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtsmiqavpj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gtloppghua.html

[R32] 参数个数校验
来源：http://dali.sysykeji.top/Article/details/gtzvsfwtjx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtldwncmzh.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotlkxhak.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pycfn.com/Article/details/gtggyiyfdj.html

[R34] 退出时清理
来源：http://dali.c1oappe.top/Article/details/gtqqqwxqrh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtnedhkxhd.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtvosnzagp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtyctmxqdl.html

[R36] 并发执行多个任务
来源：http://dali.zhixingplan.top/Article/details/gtfbzemate.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gtarmmelbe.html

[R37] 把输出赋给变量
来源：http://dali.0kj1m.cn/Article/details/gtklwiqgst.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtbhslvlbr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtyzhpbppf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sweek.top/Article/details/gthljmvssw.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtkyicavdp.html

cmd > out.log 2>&1
来源：http://dali.quarkkingdee.top/Article/details/gthjoflexh.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtzyjmvlzq.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gtgybqxprl.html

[R41] 丢弃输出
来源：http://dali.zhoulong.xyz/Article/details/gtczbbmfob.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtomtnwnve.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtewlhgtoq.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtuabuolna.html

[R43] 按名字查找文件
来源：http://dali.yj20258888.top/Article/details/gtvwtjsabx.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtptxitwht.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtxssqmupu.html

find . -mtime -7 -type f
来源：http://dali.ybcxt.top/Article/details/gtktahwdea.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtaqaganwi.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtnxcsnklw.html

[R46] 递归替换文件内容
来源：http://dali.yongpay.top/Article/details/gtjvbhnvlh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.feifeiyinyue.top/Article/details/gtnlmzokuk.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgkeossv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtdoozbqkv.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gtokytfwxj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtvfjjnhfs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gtufcjipea.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuxming.cn/Article/details/gtevljgbyo.html

[R50] awk 求和
来源：http://dali.bjfxy.top/Article/details/gtynjspnwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtdpfnqvqc.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gtmltldvqx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtepffdtwd.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtmymolqwg.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtvgwthpwy.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gttugshaqj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtqooroxbj.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtkuqssbzb.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtktfrhzsa.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtwyeeprrj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shzxlz.cn/Article/details/gtrniwqntu.html

[R56] 远程拷贝
来源：http://dali.bjfxy.top/Article/details/gtjjsutdxc.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtjigersjg.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkzsmkxei.html

ssh user@host 'uptime'
来源：http://dali.pycfn.com/Article/details/gtzmpcntet.html

[R58] 下载文件
来源：http://dali.andypj.xyz/Article/details/gtmccxobdd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jianghu66.top/Article/details/gtlsgutehr.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdosytrdo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtyshsjheq.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gthjyeziob.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.316326.xyz/Article/details/gtlvhikoot.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gtoktgenup.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtwmtcjxxp.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gteqvetkkw.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtbfujwros.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtqhfzpfct.html

free -h;  ps aux | grep nginx
来源：http://dali.yvedp.cn/Article/details/gtqrhwcvnb.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtorfeiitx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtnlhtvzvc.html

[R65] 查看端口占用
来源：http://dali.quarkkingdee.top/Article/details/gtrmxtgazh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtynchosts.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtllwtfbbv.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtaxbqhwgi.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gttyvqrwey.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtxqabbqmk.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtwgmsytwm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtlansgprc.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtcesglzww.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtmupdrrqe.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gtsubjuhhq.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtutyhokbi.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gtdaubehff.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtybvdmczj.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gttyaxqcge.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtgiurwxyj.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtsrmfzeyk.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtwenotefi.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gteqfehlwb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gtmrlykzca.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gthxhipgpi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtihfqzwfj.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtytssbhfo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtlmifdfnk.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtboqbzkiu.html

read -rp "请输入: " ans
来源：http://dali.zhiwuduotai.top/Article/details/gtysbcngvz.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gtvnovgsho.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtttixqkuj.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtvbfqejbv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtnmgjtesx.html

[R80] 查看脚本执行耗时
来源：http://dali.shzxlz.cn/Article/details/gtigiulcsp.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtrkmwrmmv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtefkqzmlf.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtbkhzekri.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfgxciwq.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gteiptumrd.html

#include <stdio.h>
来源：http://dali.dianchejie.cn/Article/details/gtgnojzjxl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtrliaigju.html

[S02] C：变量与格式化输出
来源：http://dali.wangshuangyany.cn/Article/details/gtefgwvyfv.html

int a = 10; printf("%d\n", a);
来源：http://dali.tianlin.xyz/Article/details/gtehjkvrci.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gtipvgtmyn.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtcdvosxtm.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gttjebycbm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pycfn.com/Article/details/gtrelesjwc.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gtzivzltvz.html

strlen(s)
来源：http://dali.cdnleiting.top/Article/details/gtihonswbm.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtsdqqlubv.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtiwdeifbk.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtqcpgjiys.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtndlrpwph.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtadbyalrx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtuibvauym.html

[S09] C：结构体定义与初始化
来源：http://dali.gogol.net.cn/Article/details/gtmcqovhyd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.snrcjt.cn/Article/details/gtppqcmdco.html

[S10] C：指针与解引用
来源：http://dali.cheryme.top/Article/details/gtnssovbbz.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtmrwaohvj.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtvwyydnyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtuaxjzcbd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gtzfawryrh.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazxfnlby.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtveklkrxu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtpvtavmty.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtlsqpwdng.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gtzqrzppnu.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtcnidnimz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gtihmdmszf.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gtvwbbnqgv.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtldgrqenz.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtbofzoite.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gtljukwxha.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtshddfqaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtukbhfiyj.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtjtnjhqxh.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gtjrdjcbbv.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gttloadipu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtcaawexpv.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gthpqqptrn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtxmlvvkix.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gttlitkqlt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gtpcsdgejd.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtvpjgzfnz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtvuruidmo.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtigmrlsrw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tian-w.cn/Article/details/gtcrukvpuq.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxugzgaf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yangfankeji.com/Article/details/gtycvsbdev.html

[S25] C：内存拷贝
来源：http://dali.ivvv.top/Article/details/gtaazvgwvm.html

memcpy(dst, src, n);
来源：http://dali.havefunace.top/Article/details/gtdjhobixk.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gthpnksmmt.html

memset(a, 0, sizeof a);
来源：http://dali.fzhhl.top/Article/details/gtfepmjiik.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtomophpay.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtdaazwlpa.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtcksvplia.html


<!-- 参考信息 -->