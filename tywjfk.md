代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2jldlpcig.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gt2hdngvduf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wfiqyvaf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2amylsqbz.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gt2yhtcknpy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjfjcvke.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azpovtud.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2zjalucpd.html

[Q63] 开启事务
来源：http://dali.zdqjudy.top/Article/details/gt2ntnoytpl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gt2zjaxeoyn.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gt2tajnzvas.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gt2wzvoxmqx.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gt2qqdwizka.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gt2flluhmor.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gt2sukhyona.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnxiangtu.top/Article/details/gt2umfznscr.html

[Q67] 设置隔离级别
来源：http://dali.pengpengdd.cyou/Article/details/gt2usiuixhb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2tovanswc.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gt2nqjqcqve.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gt2agvwrubs.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gt2keccnawy.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gt2pztzpfcs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gt2winxnvnt.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gt2twkkfkiq.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2knmvhgxg.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gt2ilnzgluq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsiobbed.html

[Q72] 查看索引
来源：http://dali.jinqigfzy.top/Article/details/gt2opbynmmp.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2swahwntv.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gt2mlymkkib.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gt2cjstacyi.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gt2syslcswr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gt2ztbtskvj.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2wamrmrel.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2khgojwar.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.kuanghao11.cn/Article/details/gt2neujoyvp.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gt2wieqtjdd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2abqylidq.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gt2vquwbgnj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gt2srznojre.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gt2mtcpkphp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gt2japkrtek.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2fkyatctz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gt2aodhvaia.html

[Q80] 字符串截取
来源：http://dali.jiagoushi.top/Article/details/gt2kewugado.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2rghfimtp.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2qlnhcnwq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2zlvavqkz.html

[Q82] 字符长度与字节长度
来源：http://dali.redwolf501.top/Article/details/gt2dpywwouv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2pwmkkjdz.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2bvbpicda.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2kjwrumdc.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gt2cnabfynz.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2peqrvuws.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybjrfcgz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gt2flkurmzb.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gt2dixxdvqh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gt2gsetbzcm.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gt2apnjcgpo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.fzhhl.top/Article/details/gt2nnakzcon.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gt2lpaflvie.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2gkfnzetd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2qongduim.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gt2rflnomzm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.vqdsnc.cn/Article/details/gt2xdwqandr.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwxshzrd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dashuyun.cn/Article/details/gt2murtuyze.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyiougmw.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gt2pnhbuudp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2siirrmzz.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gt2kbgezkgj.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gt2bczwjmfe.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2cezqzfeq.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gt2ukahcohq.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gt2bymbulvy.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gt2tsiqexnp.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2pstjxjdz.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gt2yecmyphd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhoulong.xyz/Article/details/gt2awheqnon.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2gacsblsk.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okplnzgq.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gt2xqtloxsf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gt2mluqwcyf.html

[R07] if 判断文件
来源：http://dali.zdqjudy.top/Article/details/gt2aoqsgfge.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2dsdhadkd.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gt2qdfrntrn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2mswohfah.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2pyngvvbs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gt2akrnqgsp.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gt2dknftipm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gt2pmxwplgq.html

[R11] case 多分支
来源：http://dali.shangyingyoupin.top/Article/details/gt2zotsbtuk.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2udiklent.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2hcyxeqsd.html

stop)  echo "停止" ;;
来源：http://dali.xziqi.cn/Article/details/gt2nkaubers.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2xtwmrpjd.html

esac
来源：http://dali.sweek.top/Article/details/gt2opxfikgs.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrchkyzi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gt2ftxsokar.html

[R13] for 计数循环
来源：http://dali.dianchejie.cn/Article/details/gt2jlpbnavs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2jxwjypye.html

[R14] C 风格 for
来源：http://dali.havefunace.top/Article/details/gt2ercmrxfz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gt2hrusvphm.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gt2fslabcrk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gt2qqezhrym.html

[R16] until 等待条件
来源：http://dali.gaohongyu789.top/Article/details/gt2eokoalwr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2bhkgudai.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gt2ovnumbmw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gt2kyzgripj.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gt2zrxbwtpg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ybcxt.top/Article/details/gt2bdpepfyh.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2yyqfexml.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2uthztymq.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gt2ixzbhvcc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gzhubu.top/Article/details/gt2cjzxhczr.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2bdlqhmzz.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2jcrklnme.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2lwzhgamw.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srxhurer.html

[R23] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2akhzccbs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2gkrdwdvn.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcumyyi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2ectolzya.html

[R25] 去后缀 / 去前缀
来源：http://dali.nwbrower.top/Article/details/gt2nrphjwcv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cdnleiting.top/Article/details/gt2cavcrmzt.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gt2ydidbbto.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gt2nuybxqnn.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2phkjzwjn.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gt2dntppqxo.html

[R28] 浮点运算
来源：http://dali.redwolf501.top/Article/details/gt2mrtgzlrc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhengqikj.top/Article/details/gt2ctscvpbx.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2dnxmqgco.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2hpjkpzcy.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gt2nlpmkbme.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hysaishi.cn/Article/details/gt2kfcbdriz.html

[R31] 局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2zmskuvfr.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gt2sdwkrfst.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gt2hpwgqbyv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2tahyaaff.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gt2kuysdtbp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.kuanghao11.cn/Article/details/gt2vntvtczv.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gt2znjxcmhe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwlfeovh.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gt2xqlwijxj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2bobtrqbh.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gt2qilpjhny.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2kvaxuwhy.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gt2xktprcti.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adducycw.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gt2jwuntrgu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cdnleiting.top/Article/details/gt2pbqdxywa.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gt2mzlqybby.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gt2wpdhwigp.html

[R40] 追加写日志
来源：http://dali.gzhubu.top/Article/details/gt2ifiqhpmq.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gt2mvuhhcuu.html

[R41] 丢弃输出
来源：http://dali.daria6918.cn/Article/details/gt2rlionumq.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gt2vtraqqub.html

[R42] 输入重定向
来源：http://dali.cheryme.top/Article/details/gt2ikgjzoks.html

wc -l < a.txt
来源：http://dali.aizwys.cn/Article/details/gt2xuwftlyk.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gt2lmyoucwy.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gt2fjfzxxms.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gt2nhfblhmf.html

find . -mtime -7 -type f
来源：http://dali.jianghu66.top/Article/details/gt2rkiytsmk.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gt2ndttzrfn.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gt2rfmtehfi.html

[R46] 递归替换文件内容
来源：http://dali.yj20258.top/Article/details/gt2hqrmhknd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yvedp.cn/Article/details/gt2cjujreds.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2upnhyuos.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gt2cojqgljr.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2tcvfiyqk.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtonfrex.html

[R49] awk 带条件
来源：http://dali.jianghu66.top/Article/details/gt2htnhoycf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gt2gfomcazh.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gt2bexlootu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxoihnre.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afvulpjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gt2xsmvylks.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gt2pemmcvbf.html

wc -l a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2yhpdkjtn.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gt2olkoqeml.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2yratzgcx.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gt2tfumpllj.html

diff a.txt b.txt
来源：http://dali.aibaodan.cn/Article/details/gt2wslwjjhv.html

[R55] 压缩与解压
来源：http://dali.andypj.xyz/Article/details/gt2fpjmiqdg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hnxiangtu.top/Article/details/gt2qupyprtn.html

[R56] 远程拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2wqlfncpy.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gt2amtfvzve.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gt2wcznqfsq.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gt2qhojbldf.html

[R58] 下载文件
来源：http://dali.ehwqpu.com/Article/details/gt2aiouxeul.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gt2obrrvitf.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gt2piliwouq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gt2zfwfzfkh.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gt2wugxdxcw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gzhubu.top/Article/details/gt2faygdebn.html

[R61] 磁盘占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2jonootcm.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gt2lmsvihod.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2lajjsvqr.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gt2bivhuall.html

[R63] 内存与进程
来源：http://dali.yuanzhike.top/Article/details/gt2czdlceyj.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gt2hmfyzpyf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgltqteu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gt2afuigfzl.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gt2lpefahck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gt2qxijdmsm.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2dlvmpkox.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gt2itqtbqpb.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gt2qhdktknr.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gt2mozedwlg.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gt2gttgarld.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2lghhxxni.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gt2xdfaeukj.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stuojwmq.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gt2kenvsaws.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdnwjfrn.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2iniarkoy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.kuanghao11.cn/Article/details/gt2lodekrtx.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phcgfymo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gt2bolykwyw.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdzlyoen.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gt2satmertm.html

[R74] 批量重命名
来源：http://dali.cheryme.top/Article/details/gt2izoxokcm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2ewyvcpnm.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2apzgxcyh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yongpay.top/Article/details/gt2fmcitonf.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gt2dhhaynsq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2ajuapmsv.html

[R77] 读取用户输入
来源：http://dali.guowangkeji.top/Article/details/gt2xomlaktp.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gt2imkabunp.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gt2tfslutfz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gt2ymwvzuek.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gt2gnuxouig.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzfjiker.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2hqpycfzq.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2meulngrr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2mkjaffoq.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2smelzuba.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2pvotrpuc.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdzdqdda.html

#include <stdio.h>
来源：http://dali.ppjwa.cn/Article/details/gt2ukfvnepq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tanke756.top/Article/details/gt2lsqenefu.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2zxlqjzty.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kocikzeo.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gt2thtovwve.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2glflslve.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gt2ubmhqqio.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gt2omcrntsu.html

[S05] C：字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2wnzgjhfg.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ztjoobkl.html

[S06] C：字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gt2cftecmms.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gt2ggpuzxxh.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gt2ttqqyyzj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edroqota.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gt2mfmjppgw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pylvbfoq.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gt2qdrfqwse.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yuxming.cn/Article/details/gt2arajexsj.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gt2jnvxsdha.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gt2uqmaqxkv.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2mtvdopoq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ehwqpu.com/Article/details/gt2ewdwbqym.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2ydwnqiot.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gt2vyujxqnx.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2srqowwqq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gt2znnhznou.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gt2jhkrkrjm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gt2pmbmaecj.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2zoeqsokh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gt2fkigyhhi.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gt2qvvjmzqp.html

(double) a / b
来源：http://dali.yonumen.top/Article/details/gt2hyurckqg.html

[S16] C：位操作置位
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xzgdswbt.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2jtomkelw.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2lgwcphby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hysaishi.cn/Article/details/gt2rdilwgpu.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2aizmxaer.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tqxamhyp.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2uifdxtwv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2zgkavhsb.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmopkeha.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxjmhcss.html

[S21] C：字符类别判断
来源：http://dali.yj20258888.top/Article/details/gt2oglfukzi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gt2yovcwwls.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gt2usstejpi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gt2hvgdhiyo.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gt2sujjfubl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gt2jsbcjfdd.html

[S24] C：获取本地时间
来源：http://dali.yongpay.top/Article/details/gt2lfqefymh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2rtbgdjwt.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2vbazibml.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gt2ulakebin.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gt2xeyqvvhy.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gt2jzdaeuji.html

[S27] C：定义常量
来源：http://dali.kuanghao11.cn/Article/details/gt2qdfelxbq.html

const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gt2wongczhe.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gt2lwsclvsj.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gt2ygkpumgt.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2autjqcrr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gt2hhhvogvf.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gt2talwmwgp.html


<!-- 参考信息 -->