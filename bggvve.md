代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtfayoxhhq.html

[Q54] 清空表
来源：http://dali.hammf.cn/Article/details/gtpaxtrxio.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gttkmrriql.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtinrbneyb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tanke756.top/Article/details/gtkbeyxcsc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtxmvvyadh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtztfcsajy.html

[Q57] 行号
来源：http://dali.daria6918.cn/Article/details/gteffxujwc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpnehdqzc.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gtddjzhfuo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtuylwxvwx.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtzohgsedi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtgwfobeba.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gthuzecdnq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtxpfziuut.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtjvvnoogk.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtmrlvvtdw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtaldblokn.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtiwgmxola.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtprilcvwu.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtzzoznhuk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gtonjnmhom.html

[Q64] 提交事务
来源：http://dali.yangfankeji.com/Article/details/gtmtkvuesi.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtyqznhtsy.html

[Q65] 回滚事务
来源：http://dali.jinqigufen.top/Article/details/gtnwfpzvum.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gthxbxcqka.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gtrtiploco.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gtekohrrzv.html

[Q67] 设置隔离级别
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtblajqbwn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtkfwurkyc.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtifltnbfj.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtkcvgckvx.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtxwuhzimx.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtfwnxlczd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtuepfyxpj.html

[Q70] 更新统计信息
来源：http://dali.cheryme.top/Article/details/gtzptshhpi.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtfqkdwmdy.html

[Q71] 查看建表语句
来源：http://dali.chenjidiqi.icu/Article/details/gtlyqhsznj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gtbtdtpvad.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkgsdehm.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gtafsdlwsj.html

[Q73] 查看表状态
来源：http://dali.jiagoushi.top/Article/details/gtarapvxav.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtznyekofn.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtyknxmuay.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkurxnfh.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtrmibanxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtgdbvyslk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gtbmutcpjg.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtbdqipkhf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtoxzyyidr.html

[Q77] 时间加减
来源：http://dali.birdmap.top/Article/details/gtgtxtfkpd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtsumxjunj.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtqojpuxly.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinghuilouyu.cn/Article/details/gthuixuwfa.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtsznisnqq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtlkenltco.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtepfcylfw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzasznfvu.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtmxcplthu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtthqfgznx.html

[Q82] 字符长度与字节长度
来源：http://dali.gaohongyu789.top/Article/details/gtrjfbnzjc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtpfeqlnqo.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtvfyuhwmr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gteabpeqov.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtuppgmknw.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtvbghbcve.html

[Q85] 数值取整
来源：http://dali.yuxming.cn/Article/details/gtmygqnbux.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtpwadjrot.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtsmrmqnxo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtgfycdwba.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawbqjdvz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tanke756.top/Article/details/gtnctqkgmm.html

[Q88] 行转列（条件聚合）
来源：http://dali.guannengcc.top/Article/details/gtyrxsjeuz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtvxxnmuet.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtilmhqiwl.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtxhlnrtcr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtbuamobqo.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtrsyyjliy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtgjcvahlm.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttkborvsm.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtbzseghzj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtifedzthc.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtbvmdhxtt.html

#!/usr/bin/env bash
来源：http://dali.cqqwz.cn/Article/details/gtzmmlfgue.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtpssgjzkz.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtmoifjjxm.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtfakymprr.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtkkuyysbo.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtyooyzsyl.html

[R04] 位置参数
来源：http://dali.svipenyu.cn/Article/details/gtdlzxjjqo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtmaxtyhtk.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtgmhgpmbc.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gtxnhvjstv.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtlpxstxhw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtvalxskku.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkrkgpug.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtcxaticaj.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtadkhavxk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtachwzkck.html

[R09] 字符串比较
来源：http://dali.zhoulong.xyz/Article/details/gtjuzysfhk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtqqrqbkkb.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtperosjrs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtbbvxrnjk.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtlewgupwl.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gtsjpxstxw.html

start) echo "启动" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtyqdguxcz.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gtmegfcmvx.html

*)     echo "未知命令" ;;
来源：http://dali.yangfankeji.com/Article/details/gtbkfbhrff.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtdviyko.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtqtivnddm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aibaodan.cn/Article/details/gthaqtdlin.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtcwxmqdrt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtsrcphimu.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtmotxfrmo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtfrixfbyn.html

[R15] while 逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtryhifden.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gtzlmcldcq.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtrexjjuuo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtgbeekqas.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtmkocijvr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtlkeyyifv.html

[R18] 遍历数组
来源：http://dali.shangyingyoupin.top/Article/details/gtwwowwbcw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gtwznsysbq.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtfxpazmsg.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemamdewp.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gttftvcxnc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvpiolcg.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtzrafespf.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtuaeyenqz.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtiqvxfrfp.html

echo "${s:0:5}"
来源：http://dali.aizwys.cn/Article/details/gtzuntxssh.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtomkrjuzd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtxoadibld.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqportnwd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtcuxtwjsz.html

[R25] 去后缀 / 去前缀
来源：http://dali.fengsongda.top/Article/details/gttrkjgjyo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xinyue.icu/Article/details/gtlgwcrjlk.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gtnlyekkdd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtupjnigdz.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtknklwcas.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtqrembsqk.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtafvbaool.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigufen.top/Article/details/gtxevwmygq.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnnijnqe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtjhuqygtt.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtxfvbwjgc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yangfankeji.com/Article/details/gtbppozdef.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtwtdgzhea.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gthioisyer.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtcwkxngpo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfkvzxos.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtmtrhfsuo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gtfhxdcdfz.html

[R34] 退出时清理
来源：http://dali.havefunace.top/Article/details/gtndfpwefs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtimpzbkac.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtnkfdbkfy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtxkxjbcpc.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtozmjxgkf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gtzsfnfleq.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtirteeawg.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gteiermrvb.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtxsxnselz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtksyupudl.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtzpamhxyr.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtibtfajoe.html

[R40] 追加写日志
来源：http://dali.hywenlv.cn/Article/details/gtzscmnvqj.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gthobpcnur.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdwhwbor.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtblrgfyce.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtuiygicuo.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtbzozpsry.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gtlsbkmwbz.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gtfxvgezol.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtzeaevrsw.html

find . -mtime -7 -type f
来源：http://dali.cucudq.cn/Article/details/gtyojxhaks.html

[R45] 批量删除
来源：http://dali.nanxinkj.top/Article/details/gtppbcijkw.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtcyjpcddd.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtkefvxlif.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtfwfpbyfq.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtmydkaofw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftmeohno.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimgnudub.html

awk '{print $1, $3}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtoxbbzdue.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtshqyncnr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gtmdqwtanr.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtmuqvplpp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtubbnslmb.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtfuijceou.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sysykeji.top/Article/details/gtwuhsiniw.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtiupmnaqx.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gtsuajjjek.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvtqkbbs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gttsxiyjqz.html

[R54] 比较两个文件
来源：http://dali.vqdsnc.cn/Article/details/gtvgkgxoht.html

diff a.txt b.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtodaoufom.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtkkglbrdm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tanke756.top/Article/details/gtipgxentc.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtzifkhmwl.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtxnyhlpxb.html

[R57] 远程执行命令
来源：http://dali.jyoumei.cn/Article/details/gtjtjhrxpa.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilvupvuz.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gttgpgrhfj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hnxiangtu.top/Article/details/gtpjnnwzkx.html

[R59] 发 POST JSON
来源：http://dali.0kj1m.cn/Article/details/gtrpwmrsdd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yuxming.cn/Article/details/gtgnfoweiw.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtumryqjua.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jianghu66.top/Article/details/gtjsovytut.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtljyunwtz.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gthoyfrurw.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrxfdbqz.html

du -ah . | sort -rh | head -10
来源：http://dali.jlsjyb.cn/Article/details/gtlmsjieci.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gteicqxwiv.html

free -h;  ps aux | grep nginx
来源：http://dali.ydzc1.top/Article/details/gtfhvgggeo.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtgcidznmm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yvedp.cn/Article/details/gtjqvhihzr.html

[R65] 查看端口占用
来源：http://dali.meibo888.top/Article/details/gtxkcfvyme.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuetiantiany.cn/Article/details/gtzclhajte.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtjwavugek.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhfurykd.html

[R67] 生成随机十六进制串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxmdhbly.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtyhhmdhqj.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtprlwprbd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtppqfzeum.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtmkibsqil.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gthosppszp.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtowcnykkj.html

date +%s;  date -d @1700000000
来源：http://dali.smart0.xyz/Article/details/gtdyxsrjcq.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtlqizjmyi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtziqmvppl.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtvothbsus.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuocryiuw.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzcnxuxh.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtcepzywjb.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gtntwwvlbq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtblruajnv.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtsdbzvlaf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.bjfxy.top/Article/details/gtthlnadaa.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtmykfuunw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtadrvesfg.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtbjlzjzbv.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtqteksrip.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtkzkonadt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtbsblqcyq.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtlmcyrjic.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cashguo.top/Article/details/gtajcsbccg.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtckiuoynk.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtmdrwebau.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcsgceygk.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtbkcfbfbg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwpvnrh.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtsrfkkakq.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtvvxujxcx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtwngtyinl.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtsfaepbqk.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtqcufhchw.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtjbmjzxrr.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtzqrgjnpx.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtkktcabdx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtkdfbtozv.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtdhlaevwp.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gthhgebnor.html

[S06] C：字符串比较
来源：http://dali.yj202588.top/Article/details/gtthwouyke.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtzmncczie.html

[S07] C：数组遍历求和
来源：http://dali.shzxlz.cn/Article/details/gtbsinizzf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sweek.top/Article/details/gtxnmwmnwj.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gtuwgceamo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtbmwqiygi.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtrxldgnbt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtgmtehkpg.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlejmffnc.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfrmfajn.html

[S11] C：逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtxvfrfmnl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gtoxrqjdqf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtcyliuzpa.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gtsrwjbpoe.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gtwfjhsyde.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtwccxywiz.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtoyajiqsl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtawzhczvn.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gthcvldcjs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yvedp.cn/Article/details/gtapiylrnb.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtwkwurexy.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtuiblwhqq.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtqfdqrvaw.html

x |= (1 << 3);
来源：http://dali.xylfe.cn/Article/details/gtelstijsi.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtpuysdtit.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtgzlzqbwp.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtnljxtydi.html

int main(int argc, char **argv)
来源：http://dali.guowangkeji.top/Article/details/gtzpsghenv.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gtblmvcvhc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtsualmhfy.html

[S20] C：二分查找
来源：http://dali.birdmap.top/Article/details/gtqjurpfpl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtryagjpkh.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtvfulbnjw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtyunztkdm.html

[S22] C：字符串转数字
来源：http://dali.cheryme.top/Article/details/gttdgajliy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtgcxowofx.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtwlkxzqnx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtwkombdme.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gtjiightnq.html


<!-- 参考信息 -->