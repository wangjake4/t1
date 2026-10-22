代发 wailian999

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gthtfldbha.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtvttpasyz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtwcinejdo.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtrfjwacoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxbuzangn.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtblgadggd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtwbjwwjyz.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtnrzgffma.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtejkhsnbu.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtlkmdexgx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gtwigvvoab.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtdnflkcua.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtowokpnvl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtmxaoknpr.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtqqgtybum.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtttxlncfa.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gtxjcorgyi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtaemdmirm.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhtixhgi.html

COMMIT;
来源：http://dali.zhongyouzk.top/Article/details/gtcrqwwbet.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjnwalqm.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtccnmuoto.html

[Q66] 行锁查询
来源：http://dali.iojbl.cn/Article/details/gtqsianbky.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtbavbukjr.html

[Q67] 设置隔离级别
来源：http://dali.aibaodan.cn/Article/details/gtsqktgcaw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtmvawyqpu.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtamjeorsl.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gthognyfqh.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gtbdztndia.html

[Q69] 查看执行计划
来源：http://dali.xinyue.icu/Article/details/gtfgmlnnlx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtcnxgnqmi.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtkqlcqvpu.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gttosqifhm.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtbixymopf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xinyue.icu/Article/details/gtpybiennh.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtnntzaynp.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtlmavcjca.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtlcojgpqw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gturwwhech.html

[Q74] 强制使用索引
来源：http://dali.tanke756.top/Article/details/gtzadovkzd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqdpgwya.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gttlxgrqmh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtsnsepffm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pycfn.com/Article/details/gtgtbihqvc.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gtmycmjpmk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gtcjidofmv.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtbisszlin.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbmuqpac.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtugktjqby.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtofgkxjnq.html

[Q79] 字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtshcfkqtk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cdnleiting.top/Article/details/gtekboukda.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtkwlpmhxs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtvuzukgqq.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gtdssoyrnn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtblifinit.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gtmvzubruk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrzwhyin.html

[Q83] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtdavfmchj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gttnvrntgm.html

[Q84] 去除首尾空格
来源：http://dali.mhx1999.top/Article/details/gthbtajhax.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfoqdnqp.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gttycalgkx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtzvpijths.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gtuglinxqw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gttfwsribk.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtfbxazjvg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtdbeivfmc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gtnzzhomqg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.haohaochexian.top/Article/details/gttzqsiudm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmjmhbymj.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtlakfkrni.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jqgfzy.top/Article/details/gtewwkjute.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtnqeilien.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sweek.top/Article/details/gtddfhvrfm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtceyasxte.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtpbnzkzex.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsidmuiby.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtiadjqmam.html

#!/usr/bin/env bash
来源：http://dali.hnxiangtu.top/Article/details/gtfafdzmnk.html

set -euo pipefail
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpbjwsmg.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtfctjsdca.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gtzvtqrlhy.html

[R03] 只读变量
来源：http://dali.yongpay.top/Article/details/gtjsdvhsre.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtvlsmrfkp.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtrauxolrr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtvtelckeu.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtvvcttxox.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtecjvlyuw.html

[R06] 判断命令是否存在
来源：http://dali.yj20258.top/Article/details/gtchvixuuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtubyvkmkw.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gtjzlxweqk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gtqzcafetr.html

[R08] 数值比较
来源：http://dali.zycfv.cn/Article/details/gttfpokowu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xziqi.cn/Article/details/gtttgfkyly.html

[R09] 字符串比较
来源：http://dali.yueranfly.top/Article/details/gtelrejhgu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtzuxtfioy.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzradrehk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtvqxkhpyt.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtoxzlttpd.html

case "$1" in
来源：http://dali.gogol.net.cn/Article/details/gtkrmdyomg.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtipbxncbj.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gtjhnfnfcc.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gtxhvrcgmr.html

esac
来源：http://dali.zhoulong.xyz/Article/details/gtngjnjklz.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtykifevuv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvbgadbg.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gthuedryis.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gttmxbbzwv.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gtfvaazkej.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtdmbqwrbn.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtgbbwmcva.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqgddict.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtjofwyijb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtfxczcygv.html

[R17] 数组定义与取值
来源：http://dali.chenlongwang.top/Article/details/gttqtuircz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtiahvwzzh.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gtwhjzcgis.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtsqtvmkce.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gtumukvtgq.html

echo "${#arr[@]}"
来源：http://dali.meibo888.top/Article/details/gtslqwlvbm.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtxnfzjfeq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmazmyno.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtmqbrycby.html

echo "${#s}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtekslkg.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtxdlpsmkl.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtehgeqnli.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtngenzmns.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtylilpxqb.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtszrbcxxe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gtcjpmemtx.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtyykiiizq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtptiizwwp.html

[R26] 命令替换
来源：http://dali.yuanzhike.top/Article/details/gtnkleqrnx.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbpbofvh.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtqzopcbke.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtfmlfoxgr.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtcguqqmyu.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpehlege.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtvubsrdcr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtegriikwf.html

[R30] 函数返回状态码
来源：http://dali.ybcxt.top/Article/details/gthbbafcar.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtevgodfbg.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtnnlnhfix.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtmzcxatqn.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gtsczoeuns.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtchdgavzh.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtyuganskg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtzbrthnea.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtzkjtbmqn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtigmcdvgf.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtbhumswjn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.c1oappe.top/Article/details/gtvbhkgtqg.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtzbpcpqmb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtvritjqdp.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gthyebvzbe.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwbdlixno.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtyhybatqi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtexrqgrev.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtdrftzxdk.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gtmjbocgrl.html

[R40] 追加写日志
来源：http://dali.tian-w.cn/Article/details/gtctfeqwlh.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gtezklevid.html

[R41] 丢弃输出
来源：http://dali.guannengcc.top/Article/details/gtvhkzqhed.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gthgzprmiy.html

[R42] 输入重定向
来源：http://dali.zhongyouzk.top/Article/details/gtextakymx.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gtbnsqtrut.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtwxlvcowd.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqwpmtyb.html

[R44] 按修改时间查找
来源：http://dali.mhx1999.top/Article/details/gtutpqvaoz.html

find . -mtime -7 -type f
来源：http://dali.yuanzhike.top/Article/details/gtsanuutzd.html

[R45] 批量删除
来源：http://dali.aizwys.cn/Article/details/gtykaziawn.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtvwotltnv.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gthcbjszqb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqipkclbw.html

[R47] sed 单行替换
来源：http://dali.0kj1m.cn/Article/details/gtnhrdvbzg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gthusmktpj.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtdyvdnsmj.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtdylcaoev.html

[R49] awk 带条件
来源：http://dali.wangdashe.top/Article/details/gtmtoxbmmc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.kuanghao11.cn/Article/details/gtzzthdqyf.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtzokkjkmt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtntljtzue.html

[R51] 排序去重取前几
来源：http://dali.wangdashe.top/Article/details/gttsxofuas.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtcmamajtr.html

[R52] 统计行数
来源：http://dali.shangyingyoupin.top/Article/details/gtapiukfzf.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtpkppsyos.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtmrzzzgqq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gtgfedcdvl.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gtlpjsfmzh.html

diff a.txt b.txt
来源：http://dali.daria6918.cn/Article/details/gtbdfhdqmh.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtdrxqjerq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxuanxn.top/Article/details/gtvfqjjbvl.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznfrzjxn.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtirycervk.html

[R57] 远程执行命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxfgijeoc.html

ssh user@host 'uptime'
来源：http://dali.316326.xyz/Article/details/gthosumtab.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtxvwkhadz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtvhchhhgo.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtvmsvgesz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtkpcjdfbc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtuifrrdnh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtretwgxmc.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtxmmauncw.html

df -h;  du -sh *
来源：http://dali.gogol.net.cn/Article/details/gtjvdrcxiq.html

[R62] 找最占空间的文件
来源：http://dali.yangfankeji.com/Article/details/gtgegvlyxu.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnotzvqxg.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtaujstffg.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtcpskculi.html

[R64] 结束进程
来源：http://dali.wangdashe.top/Article/details/gtaznhchil.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gteplcwbtg.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtrldawjwx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtvhhmbaxk.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtgvqgizfb.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtdefavjub.html

[R67] 生成随机十六进制串
来源：http://dali.yj202588.top/Article/details/gtpeqhtoli.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtdeasxckv.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtlphsgkzh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtlndyuixk.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gtzqhpeenn.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtineefxlz.html

[R70] 时间戳与互转
来源：http://dali.wangdashe.top/Article/details/gtumferfmc.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtloinmstf.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtkkqjfcbo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtekbhgkxp.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtvkqxrrfe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtzlhtaxva.html

[R73] 分割大日志
来源：http://dali.quarkkingdee.top/Article/details/gtxsjjstxe.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtdhmyljyg.html

[R74] 批量重命名
来源：http://dali.jqgfzy.top/Article/details/gttlulpfaf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtyntyvnec.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gtkgezuliu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gtoozngmqo.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtnvskirvd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtdrfdmqco.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtqpnqknwc.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gthmskbvvx.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtvtnrtdvj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtywuhtnki.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtqbivircc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gtsbaujywg.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtlvhrjliq.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtkmcmmjyv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkdmctaws.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtrhcfjttj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtbivojdno.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtvntohchn.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtqpjuayvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtlgdhqkrr.html

[S02] C：变量与格式化输出
来源：http://dali.gotoacloud.top/Article/details/gtlecllked.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gtvbelloei.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gtfeokaclj.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtviiolsjr.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gtxfwlauni.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtbyocebpa.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gteqgfptzj.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtyfglkfgl.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflgyzxjy.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtmvoehjpc.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gtdrslloqf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtycxoidzj.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtugvqoyak.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtyxvmdvfs.html

[S09] C：结构体定义与初始化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwwkshbk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtlejdmxce.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtczsswwrd.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gtmkkufpxd.html

[S11] C：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtttgcause.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtmqqjliwu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.svipenyu.cn/Article/details/gtdjuydsle.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtocuwosdy.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtuswvgxte.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtkzhgzwxt.html

[S13] C：宏定义
来源：http://dali.yuanzhike.top/Article/details/gttdpauklz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gtsxzsxpgb.html

[S14] C：枚举
来源：http://dali.ydzc1.top/Article/details/gtoqsmwdwz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtiikzphea.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtvtgzarfh.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtssaaldap.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gtqkcjfmad.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvcnfvfw.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtkchlabmm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtojxcsvgd.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gttmckeomd.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtjixuyfof.html

[S19] C：快速排序
来源：http://dali.shangyingyoupin.top/Article/details/gtiaopzgns.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtwupghfhn.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtxfercace.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gtscwrgzcg.html

[S21] C：字符类别判断
来源：http://dali.meibo888.top/Article/details/gtnvznbocp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gturxfzeoa.html

[S22] C：字符串转数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwscajtfe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtqzdalomd.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtsyfivixk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtwgazchsy.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtszkifaun.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gthozaxhuk.html

[S25] C：内存拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtbsujvnss.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gtwnprapzv.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtiwwryrrx.html


<!-- 参考信息 -->