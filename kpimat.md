代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtuxwlzyav.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtpcpzqkqv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtnwdofmzc.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtkekggwya.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtfongqfve.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtxwcrsgwz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdifpsap.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtgeztnklq.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtjvwfqjxc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtealknsqx.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnttwymeg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtososaqaw.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtpjlqnjwf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gtmxexszpc.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gtrjzhyzjy.html

COMMIT;
来源：http://dali.c1oappe.top/Article/details/gtyuhhulbv.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmmijnov.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtblvzcjgc.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtljllfuyf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gtbkyaolqn.html

[Q67] 设置隔离级别
来源：http://dali.gaohongyu789.top/Article/details/gtmhzmzyvx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtostkqqwn.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtksfaezfv.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtwylohqdh.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtutxpqjvs.html

[Q69] 查看执行计划
来源：http://dali.zhiwuduotai.top/Article/details/gtmaoqxiae.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzogjsmg.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gthmhujact.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gtwfediwvj.html

[Q71] 查看建表语句
来源：http://dali.ydzc1.top/Article/details/gtjrvylwid.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsirimvmq.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtqwaxyjky.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtrfushtqx.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtjkreguna.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtupsjaijk.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtcppmheqn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtkcohnhpq.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtqamdunip.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtaympaupi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtluxkditq.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtodasiokl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gtudewonfr.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtaexfjque.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jlsjyb.cn/Article/details/gtiybgvoto.html

[Q78] 当前时间
来源：http://dali.hnqzz.top/Article/details/gtkakmtttq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtzwehapvi.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtizlmgcli.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gtapufsjck.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtqvntuvve.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtvdifwxwm.html

[Q81] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtjjefjvkh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtnatgueef.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtsetqdjnl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtiuhghpbu.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtqlioznix.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtuvwyjozr.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtfbqxwvtm.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtzoeruvcd.html

[Q85] 数值取整
来源：http://dali.gogol.net.cn/Article/details/gtrkcclypa.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtrveiabtk.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtpufhhgih.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yonumen.top/Article/details/gtwcsdymww.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gtqmtobtyr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gtoploglja.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtguyharbt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtoyrzytzr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtedyfdofh.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtbptbpjlq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jianghu66.top/Article/details/gtqnftftlj.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtkecynnnc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gtdtsjmtgt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkoigziji.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtjgyzdeep.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtfgxboscz.html

[R01] shebang 与严格模式
来源：http://dali.zhoulong.xyz/Article/details/gtmorgvhaw.html

#!/usr/bin/env bash
来源：http://dali.chenzaomai.com/Article/details/gtgosfrdxd.html

set -euo pipefail
来源：http://dali.yangfankeji.com/Article/details/gtzvgicpjj.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtxbpntfka.html

name="Tom"; echo "$name"
来源：http://dali.havefunace.top/Article/details/gtegbeepdo.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtkczjbybi.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtgsoxhful.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtqdilknjp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtvvotdvmo.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtmtdrsvgw.html

name="${1:-default}"
来源：http://dali.316326.xyz/Article/details/gtszrfityk.html

[R06] 判断命令是否存在
来源：http://dali.nanxinkj.top/Article/details/gtccbuyklp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gtdzthkjhy.html

[R07] if 判断文件
来源：http://dali.ivvv.top/Article/details/gtyqahtoav.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtpnwirsdv.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvnpteny.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtnnqkottq.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtrvvlnsre.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtitvwdaen.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtpyefhrxg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.havefunace.top/Article/details/gttkvjabqk.html

[R11] case 多分支
来源：http://dali.jlsjyb.cn/Article/details/gtveglggnj.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtehekyfpw.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtaupibngk.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gttyifdrvn.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtcuzzuupg.html

esac
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsytjhug.html

[R12] for 遍历文件
来源：http://dali.jinqigufen.top/Article/details/gttkudhhyv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xziqi.cn/Article/details/gtxvtzjshc.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtwmutvvml.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gtwvovlzeh.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gttqjexpzq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtzarumkni.html

[R15] while 逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtafidjkqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtfxwciwsz.html

[R16] until 等待条件
来源：http://dali.jyoumei.cn/Article/details/gtdexecatr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtyyuizrdp.html

[R17] 数组定义与取值
来源：http://dali.gzhubu.top/Article/details/gtkfjtcbhi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtmthkkzed.html

[R18] 遍历数组
来源：http://dali.sweek.top/Article/details/gtmlibktbf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhixingplan.top/Article/details/gtthaefwto.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtxhtcmfew.html

echo "${#arr[@]}"
来源：http://dali.cqqwz.cn/Article/details/gtfvzwndjk.html

[R20] 关联数组（字典）
来源：http://dali.jianghu66.top/Article/details/gtzpirdzhj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtrznsvono.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtbtbemypb.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtteiinmml.html

[R22] 截取子串
来源：http://dali.sysykeji.top/Article/details/gtnmwejrvz.html

echo "${s:0:5}"
来源：http://dali.shuidangran.top/Article/details/gtzovsoezt.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtljvzjgmf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangshuangyany.cn/Article/details/gtgmcpagfv.html

[R24] 大小写转换
来源：http://dali.yj20258.top/Article/details/gttcovwgdv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxuanxn.top/Article/details/gtjryranzb.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtegyrpedc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hywenlv.cn/Article/details/gtdnyvehcv.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtlhgtfabr.html

now=$(date +%F); echo "$now"
来源：http://dali.guowangkeji.top/Article/details/gtkulezvig.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtmrgawuhm.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gttdzofpsc.html

[R28] 浮点运算
来源：http://dali.xylfe.cn/Article/details/gtvpnqbhim.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtkkqhvmru.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtvnaptrtc.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sysykeji.top/Article/details/gtqfoshamp.html

[R30] 函数返回状态码
来源：http://dali.nanxinkj.top/Article/details/gtfywixuox.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.kuanghao11.cn/Article/details/gtkbgnkbrp.html

[R31] 局部变量
来源：http://dali.hysaishi.cn/Article/details/gtwbdbjcqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtrwihqdvf.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtfnjzxrvd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hfpthk.cn/Article/details/gtkxdpwzpb.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtjnavzbgt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.vqdsnc.cn/Article/details/gtjrlydaxc.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtybadkwyc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gttclfqyhp.html

[R35] 后台执行并等待
来源：http://dali.pycfn.com/Article/details/gtnrvdseek.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gtbptinqli.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtrrvomtbv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtbyfjqzxf.html

[R37] 把输出赋给变量
来源：http://dali.yangfankeji.com/Article/details/gtuxtsabne.html

files=$(ls -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqdhkwzjd.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtuesimktf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtpugdxcva.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtxklxdlgq.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtlworhdxt.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtnaghhsbz.html

echo "log" >> out.log
来源：http://dali.zhiwuduotai.top/Article/details/gtmjrxleym.html

[R41] 丢弃输出
来源：http://dali.tanke756.top/Article/details/gtfmcvpwka.html

cmd >/dev/null 2>&1
来源：http://dali.shuidangran.top/Article/details/gtocyeftaa.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtqfjdtqdd.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtsqjmibzc.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gttrqbtwjl.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gteeyclmtj.html

[R44] 按修改时间查找
来源：http://dali.yj202588.top/Article/details/gtnygaivqj.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gttlverhzr.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gtvutjapvl.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtfjhcqpme.html

[R46] 递归替换文件内容
来源：http://dali.birdmap.top/Article/details/gtheyulgwd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtgkzvjsej.html

[R47] sed 单行替换
来源：http://dali.daxiang520.top/Article/details/gtfbnbyvmn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangdashe.top/Article/details/gtihqauxqb.html

[R48] awk 取指定列
来源：http://dali.zycfv.cn/Article/details/gtiortmxke.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtujfaoblk.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtvivffsru.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gtapffjpuq.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtttagmbzv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtzlgehwmm.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtobnpnmdz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtrsuqkjiv.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtfbtrvoxi.html

wc -l a.txt
来源：http://dali.yuanzhike.top/Article/details/gtdssmtwlm.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtoqumbxym.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtbuvvztbs.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gtzmhhkner.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyumwxetd.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gtrkdtcksd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gtjeiocmsw.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtholapixx.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtpfquauym.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtybpillvb.html

ssh user@host 'uptime'
来源：http://dali.0kj1m.cn/Article/details/gtvgaoxqie.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtpstjwaqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.redwolf501.top/Article/details/gtinnlamrf.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtycmojhjt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nwbrower.top/Article/details/gtnykpppdo.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gthsvyqbyj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xinyue.icu/Article/details/gtyjbjtntf.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gtgolfwbkg.html

df -h;  du -sh *
来源：http://dali.nanxinkj.top/Article/details/gtjgirgcpc.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtgimcjydf.html

du -ah . | sort -rh | head -10
来源：http://dali.cashguo.top/Article/details/gtiinmieyk.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gtfmpiuxjn.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gtblkeszeg.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtrolouwcv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwcfcudr.html

[R65] 查看端口占用
来源：http://dali.gogol.net.cn/Article/details/gtcyknpdvc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwymqcsbg.html

[R66] 定时任务
来源：http://dali.hysaishi.cn/Article/details/gtbmkhrumm.html

crontab -e;  crontab -l
来源：http://dali.tian-w.cn/Article/details/gtqllwdttr.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gttwyxdrhu.html

openssl rand -hex 16
来源：http://dali.zhongyouzk.top/Article/details/gttfwguysp.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtsrxhcein.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gthvxhuodk.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtvcbdwsqz.html

head -c 16 /dev/urandom | base64
来源：http://dali.hfpthk.cn/Article/details/gtttvfbwbc.html

[R70] 时间戳与互转
来源：http://dali.chenjidiqi.icu/Article/details/gtcgljskau.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtzcrnsxxd.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gttlxunxjg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yueranfly.top/Article/details/gtnlqjnlgf.html

[R72] 等待端口就绪
来源：http://dali.hfpthk.cn/Article/details/gtylwnbvda.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtorctmjya.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtvyfwidds.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtajdryocb.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtociapfnn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gthieoqinv.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzmqkrjua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtvxmkwpqm.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gtqcuaykst.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtmcmotlhu.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtjdmslacs.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtjyqcehvh.html

[R78] 交互式菜单
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssqlkvcf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gthhcdxotr.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtlnsrbwbo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtptowvxbx.html

[R80] 查看脚本执行耗时
来源：http://dali.shangyingyoupin.top/Article/details/gtpnwopnio.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtsbxecsla.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtalmyybly.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtugfofoot.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsaawblzk.html

[S01] C：Hello World
来源：http://dali.gzhubu.top/Article/details/gtjeyqbmmt.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtlpekxgdr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtyyxljjiw.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtovqeshtn.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtyluphvrx.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gtsxqmiray.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtfnbaoeqa.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtvzkqcvbt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtuyyholti.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtlockqcqr.html

strlen(s)
来源：http://dali.316326.xyz/Article/details/gtersrudpc.html

[S06] C：字符串比较
来源：http://dali.daria6918.cn/Article/details/gtrvaucgvq.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtzfrejawg.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujahjzlx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gtmcuhmqbd.html

[S08] C：动态内存分配与释放
来源：http://dali.nanxinkj.top/Article/details/gtmoblfwig.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtxerctasu.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gtbhtbwqha.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtrwpaerrp.html

[S10] C：指针与解引用
来源：http://dali.shuidangran.top/Article/details/gtmufvgdlv.html

int *p = &a;  *p = 5;
来源：http://dali.hywenlv.cn/Article/details/gtfrtqsbfk.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtdeivjhea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtxtolcoxf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtdscgygxf.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcurvacnf.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtmvvaakeb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtyrtowbry.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtrjiitmye.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtsseyoazf.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gthoazrmqa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuanzx.com/Article/details/gtfsdyblek.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtrrndmcid.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtwanfzucf.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtjqmumxuu.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtmosimelc.html

[S17] C：安全拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtgfmplicu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yonumen.top/Article/details/gtetfpvgvi.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtvuqwkckf.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiintcep.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpnlaify.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtmvqujnsx.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtffmcyrzn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtqueqfcrl.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtxevonjpr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtnzunqsrc.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtpdiqvlrr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtwfcwgwve.html

[S23] C：随机数
来源：http://dali.yangfankeji.com/Article/details/gtsgjhnfqb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsegzvngi.html

[S24] C：获取本地时间
来源：http://dali.bjfxy.top/Article/details/gtslmxqdcs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtejewcaga.html

[S25] C：内存拷贝
来源：http://dali.shuidangran.top/Article/details/gtzemcvswk.html

memcpy(dst, src, n);
来源：http://dali.cucudq.cn/Article/details/gtcnpocdqk.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gthrakjmev.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtkekiwpan.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtpyxfqgxz.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtazrogwfu.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtttsrczim.html


<!-- 参考信息 -->