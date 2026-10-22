代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtvwyiggzd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtkxkcuoav.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtpxvkcsmo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtrduatuxi.html

[Q61] 移动平均
来源：http://dali.sysykeji.top/Article/details/gtittwggbw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtyaifrmkt.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gtufjmyxik.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtklspkokm.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtesrviohc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtbycdolfr.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gttolofskx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtsqxnozgm.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtkspwaxgk.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gtbmwxlyzm.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtgwunjspk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtjbbdbaug.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gthpibeiwd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtuwsxlpsp.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtiwxtxzll.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtomaqfaub.html

ROLLBACK TO sp1;
来源：http://dali.yj20258.top/Article/details/gtbbjoxeqd.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtgaujjbyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xuanzx.com/Article/details/gtmcycvvtu.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtjioycjtm.html

ANALYZE TABLE users;
来源：http://dali.c1oappe.top/Article/details/gtrhnblagz.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gtponlgulv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gtnncsidlr.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtvdcrzkyh.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtqenjdkci.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbpwgxyl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtokvsgowb.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gttycgbrtq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtpgsfbpwv.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtocdztmfg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtxnprhpja.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtudzkaany.html

[Q76] 按天统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxtxctah.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtuoawubcx.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gtrcxqxspo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gttwydvlki.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtidsjsxcx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gtddckjiar.html

[Q79] 字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtrporyrdv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtmxvqicyf.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gthfpqipfh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtvjumftcu.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbsheqwa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtbhfdiuih.html

[Q82] 字符长度与字节长度
来源：http://dali.iojbl.cn/Article/details/gtfpwncgac.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtehxmmvjt.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gthabltukp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gteoiwzyus.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gtlursxfqz.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtpacojggo.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gttmqftnyi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtqrpltiqp.html

[Q86] 读取 JSON 字段
来源：http://dali.yonumen.top/Article/details/gtqmkdmfna.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtgvuxxjre.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtcqnxozxe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtclnzpliq.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gtojeodlnz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gtmffwxpoh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtygmjivli.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtbgsaiacc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtidyiogeg.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtnyjnimyr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyytrswgi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthavknvea.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtgzhiillj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsvdocngn.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtzmzyedvg.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gttkhduupm.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gteziihqcs.html

[R02] 变量赋值与使用
来源：http://dali.ybcxt.top/Article/details/gtnudlikth.html

name="Tom"; echo "$name"
来源：http://dali.xinyue.icu/Article/details/gtbqfitdnp.html

[R03] 只读变量
来源：http://dali.zhoulong.xyz/Article/details/gtpruxdgwj.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplbelcho.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gtzrzmdrpk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gttnmudqxy.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gtefchofvy.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtprrvfyzv.html

[R06] 判断命令是否存在
来源：http://dali.guannengcc.top/Article/details/gtyejoxitc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtzmqfhrnz.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaojjiqrb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gteopcvdxk.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtstfiwdbc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtbvoxkokg.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gticrtcbnw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtoslunmhx.html

[R10] 正则匹配
来源：http://dali.bjfxy.top/Article/details/gtvmfnjkfi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtcedtdvuo.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtbgrcufbc.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtztszicas.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtqtgjoaos.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtlcrytjpw.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtzswidbzb.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpktjaftm.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtlfiwhjnn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtoxyyfpub.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtftmiivit.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtirdocycz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtdjfphrsg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtnppmgmdm.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtflysvnmv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtsimiuouu.html

[R16] until 等待条件
来源：http://dali.316326.xyz/Article/details/gtrghecvdd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtyypmjuog.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gttdjpqggb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtgezqvldp.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtojtzyckp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.havefunace.top/Article/details/gtavteiwnv.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtbexbfllg.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtmarjxaac.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtmphjiyrl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtyabfzeit.html

[R21] 字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtojncmdle.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gteqcmzitc.html

[R22] 截取子串
来源：http://dali.hammf.cn/Article/details/gtjulpqsga.html

echo "${s:0:5}"
来源：http://dali.yuxming.cn/Article/details/gtbkbwlvrx.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtjjshuynv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtmgwrwgiu.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtsduuwreg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtjjffunvu.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtbqjwbjzu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhoulong.xyz/Article/details/gtlgerkili.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtznzminoc.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtkhoqtccf.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtsrkbcxre.html

echo $((1 + 2 * 3))
来源：http://dali.gzhubu.top/Article/details/gtlqdnmmuv.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtvuzmjdid.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtwwkfsaic.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtrahrweto.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtnlbgoaaq.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gttsbaszwz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gotoacloud.top/Article/details/gtfzajkxwf.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtmxzohktj.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitkblire.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gttypbahpw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmelwlmxp.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgufenzy.top/Article/details/gtjnpyyxbe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtbgwavzae.html

[R34] 退出时清理
来源：http://dali.zhixingplan.top/Article/details/gthtyeqzji.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gtqsevndtr.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtsqmdosym.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gthscoitvj.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtjsjkbnas.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtaksjtnxx.html

[R37] 把输出赋给变量
来源：http://dali.zhongyouzk.top/Article/details/gtywfdffmj.html

files=$(ls -1)
来源：http://dali.tian-w.cn/Article/details/gttpwvewnt.html

[R38] 管道串联
来源：http://dali.cqqwz.cn/Article/details/gtjwwnzhkd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtnoshizzd.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gtbwefpkbz.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtcqjgnjbz.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtsgftxeyl.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtrynjhgqf.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtjusafehk.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtolemjjsr.html

[R42] 输入重定向
来源：http://dali.ehwqpu.com/Article/details/gthtyvojgc.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqgrvtqr.html

[R43] 按名字查找文件
来源：http://dali.sweek.top/Article/details/gtjdqjkuzq.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidodullt.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gteoyeqpud.html

find . -mtime -7 -type f
来源：http://dali.xuanzx.com/Article/details/gteytsxeux.html

[R45] 批量删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhjdkbjh.html

find . -name "*.tmp" -delete
来源：http://dali.shuidangran.top/Article/details/gtseudepmq.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtsicukujz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gtjjaaahju.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtfyygubyg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtearbbrhr.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtcqlmenja.html

awk '{print $1, $3}' a.txt
来源：http://dali.wangdashe.top/Article/details/gtawptrmeu.html

[R49] awk 带条件
来源：http://dali.svipenyu.cn/Article/details/gtjxnpnssq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtifxnahay.html

[R50] awk 求和
来源：http://dali.zhoulong.xyz/Article/details/gtwgspnjem.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtquggsbbe.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtdmcspalz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gotoacloud.top/Article/details/gtvcxdrcqs.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtqhffetzo.html

wc -l a.txt
来源：http://dali.nanxinkj.top/Article/details/gtngqchanf.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gtvybmobvp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbukgwiu.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtmmrqnccc.html

diff a.txt b.txt
来源：http://dali.tian-w.cn/Article/details/gtrsdfzafa.html

[R55] 压缩与解压
来源：http://dali.ppjwa.cn/Article/details/gtjqgwiynb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtpdhcsqkp.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gtybnbrkwm.html

scp file user@host:/path/
来源：http://dali.tanke756.top/Article/details/gtnehzwncb.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gtzbzwload.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtcdzqhzfr.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtydgyfllc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gthukdrbwl.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtmoufewos.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtoocgwdlb.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gtuuovqczh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtchbdxucg.html

[R61] 磁盘占用
来源：http://dali.aizwys.cn/Article/details/gthbjvvrkt.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtckfjcrlj.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtssuyofdv.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtvvzoncrj.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtonovboxs.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gterhkfcou.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gtvdqbgqak.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuxming.cn/Article/details/gtspwjdyaf.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtywpiqvhg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtzdeyorhc.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gthukvypwa.html

crontab -e;  crontab -l
来源：http://dali.mhx1999.top/Article/details/gtuctsdote.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtggxqmyca.html

openssl rand -hex 16
来源：http://dali.hammf.cn/Article/details/gtgjpstevl.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gtiunefojg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ppjwa.cn/Article/details/gtbfbsaqrv.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtbrtgmxry.html

head -c 16 /dev/urandom | base64
来源：http://dali.zdqjudy.top/Article/details/gtfbxrxxub.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gteeausfdc.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtbbysldps.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gttyxsrdzw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtglqhorbz.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtujeysyqb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtvoopbudp.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gtwtrvlwoa.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtcexazvnf.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtcnznvhki.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtzjurgmhe.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gthcuzvenz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtvkrvwdmu.html

[R76] 使用临时文件
来源：http://dali.xziqi.cn/Article/details/gthvfneoce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gthluwtsmk.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gttxcmomwu.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gttqcvrdon.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtnubvmijy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtxgiarvud.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gtxzdwosqm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtussifbsb.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtofzkubet.html

time ./run.sh
来源：http://dali.yanxiufei.cn/Article/details/gtzicbmcug.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgikpxlhk.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtvlfnapmu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwfqbxnfg.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gtbvskcjqd.html

#include <stdio.h>
来源：http://dali.tianlin.xyz/Article/details/gtabgktlnk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtocnieuuf.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gttnypryhd.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtaszasjbv.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtijrycfjs.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtyqsnyzzf.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtwugxnlkf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtjadljhzr.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtccowavsd.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gtisjkcxpc.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gtcvkcoerw.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnzbkcbj.html

[S07] C：数组遍历求和
来源：http://dali.0kj1m.cn/Article/details/gtbrnozepj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmuollff.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtodnxnzgh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gotoacloud.top/Article/details/gtkuaagfhc.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gthwtxnfwk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtfpaviymj.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gtaewigxrw.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtgsurblhw.html

[S11] C：逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtjmpbedea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gtgovhlflm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtkdklevcn.html

fclose(f);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbvorrmb.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtmgyfkziv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtqerpbavx.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtnlrlojcx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtrcqdijwt.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtmdnybyna.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtfbnqgtnu.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtjuujsjsu.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gthzqgucos.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtljichwbc.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtwngdvoyj.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtmdqoakib.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtntezwjqd.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtvvmcozhq.html

int main(int argc, char **argv)
来源：http://dali.9152youxi.cn/Article/details/gtbxpactgn.html

[S19] C：快速排序
来源：http://dali.wangshuangyany.cn/Article/details/gtirxnrwqb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtenmpjwwy.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gthibdmmul.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtfuwbbgow.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtywfjmwis.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtkcwyulki.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtisiopkqk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtydccogrg.html

[S23] C：随机数
来源：http://dali.cheryme.top/Article/details/gtvrbicqow.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtbddgfnso.html

[S24] C：获取本地时间
来源：http://dali.wangshuangyany.cn/Article/details/gtgsmnjwtl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtxsknufdj.html

[S25] C：内存拷贝
来源：http://dali.yj202588.top/Article/details/gtrsownvcj.html

memcpy(dst, src, n);
来源：http://dali.chenzaomai.com/Article/details/gtiozrhdpw.html

[S26] C：内存清零
来源：http://dali.nanxuanxn.top/Article/details/gtaiuvljif.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvucsdvzq.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtepvpaaou.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtbhyoigho.html

[S28] C：静态变量
来源：http://dali.hfpthk.cn/Article/details/gtvkqckyln.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gtutvbgxwp.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtjvyblkem.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtpliyspfo.html

[S30] C：头文件保护
来源：http://dali.haohaochexian.top/Article/details/gtwihngzyl.html


<!-- 参考信息 -->