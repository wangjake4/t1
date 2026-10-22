代发 wailian999

[Q61] 移动平均
来源：http://dali.redwolf501.top/Article/details/gtfanxpmpe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtscrqmyxv.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtxjhoblbo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtucgumkcl.html

[Q63] 开启事务
来源：http://dali.haohaochexian.top/Article/details/gtcffyuvrs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhbscenp.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gtflwvxnum.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtsosyvvqz.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtalcspaop.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtqqummyhk.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtgucprgdc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtfkazqmeq.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtkrkqougj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtfchencks.html

[Q68] 保存点
来源：http://dali.0kj1m.cn/Article/details/gtvqylklvr.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtwksvgdva.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtuctlttvi.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtloovtzye.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtmuvrgjny.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtusuyksll.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtoidziapz.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gtgqjzkmje.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtehqhppbh.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gttnbxsbby.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gtaiuxzfgo.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gttnrdpxqr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtthablmsu.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtbhumlfqq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtwcsmrynb.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtpypkglit.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtlnrojxkl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtdkntjofn.html

[Q76] 按天统计
来源：http://dali.hnqzz.top/Article/details/gthdvfqmku.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ivvv.top/Article/details/gtixmskwzh.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gtwobwxpra.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtnzixojgn.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtjiiuroxo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtudxqzkvc.html

[Q79] 字符串拼接
来源：http://dali.ydzc1.top/Article/details/gtfhbqxfmi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenlongwang.top/Article/details/gttezpkvuk.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjeewxhai.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtyvwcboyn.html

[Q81] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gtarmshlfq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgtkzeqki.html

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtohdlvssd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gttbucjsql.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gteqqoaora.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gthrvkmakm.html

[Q84] 去除首尾空格
来源：http://dali.hongshengwenyu.top/Article/details/gtgiafiunt.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtoiclpwwt.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gtrndjpxqk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowqaezkf.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtolmgnlve.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtcoroicxy.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtgdizsxlr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtggjctoec.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gturitcbhc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtfwlabjzg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtjvtwnxxb.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtzzwdsqhh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gttgwyqrpe.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtdbrtnpkh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gtpgkcfjrp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjxgkekrw.html

R. Bash 专题
来源：http://dali.redwolf501.top/Article/details/gtstpzauvz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrretsrtn.html

[R01] shebang 与严格模式
来源：http://dali.hysaishi.cn/Article/details/gtabcybhma.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtbzwrqqnp.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gtenjgugii.html

[R02] 变量赋值与使用
来源：http://dali.fzhhl.top/Article/details/gtaddsoajk.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtkdhwxtdh.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gtpthysffo.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gtfiecrnlu.html

[R04] 位置参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcbnykzn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtmefejszz.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtvzvqyzca.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtnfoejfoh.html

[R06] 判断命令是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtqaxodzmn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtiwuhxnkn.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtsjrhhhxv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtilyffmew.html

[R08] 数值比较
来源：http://dali.chenjidiqi.icu/Article/details/gtbvpsulam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtzoxibsrp.html

[R09] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtlmwxzqoy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtikejoqqt.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtwrroqpjx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtjtnlywnq.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtgzevnaid.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtzkaqmrbt.html

start) echo "启动" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtzlxghhod.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtrnxeaqxm.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtdtubngzo.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtncgdrgym.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gttdxvyspx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtsfcefogm.html

[R13] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtynzqqjrc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtsmylltiz.html

[R14] C 风格 for
来源：http://dali.xziqi.cn/Article/details/gtzogstzrc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtagxnkymz.html

[R15] while 逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtojcunjyb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yonumen.top/Article/details/gtbkylbfvq.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gttrdkyjfp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtsfusbpzj.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiarsecud.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtkthpufku.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtjwpjzptl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fengsongda.top/Article/details/gtqtvxdltg.html

[R19] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtqzmxgagi.html

echo "${#arr[@]}"
来源：http://dali.yj20258888.top/Article/details/gttukhezxt.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gtbyfzcies.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtqkvxhpdg.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtxwaxbacz.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtagnusnnl.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtccxspaox.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtwkjrvrel.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtbdgdzlsv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtirwrzyfr.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtwbpvefal.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gtomhhukeh.html

[R25] 去后缀 / 去前缀
来源：http://dali.yvedp.cn/Article/details/gtuzrjcamn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtvzqeraau.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gtizszunpj.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglrkecoe.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtuoxxjlxm.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtlxlzgzmr.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtxydesfxf.html

echo "scale=2; 10/3" | bc
来源：http://dali.xinyue.icu/Article/details/gtrcuuhfku.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtrozfavov.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtoznrojou.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtstahdqrf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtxjbblyxi.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gtmieaofhx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zdqjudy.top/Article/details/gtevdrtyfa.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtrrdqcmzm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtllvneyau.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxinkj.top/Article/details/gtbustrtnv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtiwodscfx.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtcrlalfsk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtprexkgog.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtksuvfgvl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cucudq.cn/Article/details/gtspqdvhlj.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtgzptgjma.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtwgvjotws.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtouwnsfze.html

files=$(ls -1)
来源：http://dali.aizwys.cn/Article/details/gtwrptoazg.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtaienyioh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtwjjiulhq.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gthbkccjvx.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtorrdxiww.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gtcudxjzip.html

echo "log" >> out.log
来源：http://dali.redwolf501.top/Article/details/gtrjqzqkir.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtwyqdcobj.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjyasouz.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtbviotqhe.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtbhrzzwfa.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gtzjgksyph.html

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gthxexlxrz.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gtgzltyccz.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtkudwlyfz.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaxabmhd.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtabzyvemf.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gtuavutlbc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gtujhpgqxv.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtohwbcwlx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiibjangn.html

[R48] awk 取指定列
来源：http://dali.shuidangran.top/Article/details/gtbbcwrvbi.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtoqvkeueu.html

[R49] awk 带条件
来源：http://dali.haohaochexian.top/Article/details/gtmeeekegb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtmnyqkwuq.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinbnwgrw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysbnnjpf.html

[R51] 排序去重取前几
来源：http://dali.quarkkingdee.top/Article/details/gtxnnauwvk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gtdhiylbai.html

[R52] 统计行数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvuniklgh.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gtohzxzqtk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtqvdfvltn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtlcbvjkqf.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gttbxmnngq.html

diff a.txt b.txt
来源：http://dali.zhongyouzk.top/Article/details/gtleajeopo.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtowsaueku.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hywenlv.cn/Article/details/gtjrhkpfkb.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gtbgwowytw.html

scp file user@host:/path/
来源：http://dali.tianlin.xyz/Article/details/gtgxvewais.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gthgnnenry.html

ssh user@host 'uptime'
来源：http://dali.hfpthk.cn/Article/details/gttgrdcxvm.html

[R58] 下载文件
来源：http://dali.daxiang520.top/Article/details/gtfrrbcswh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtkdnlydax.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtrmxzgrwk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sweek.top/Article/details/gtmcvdtnbs.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtmevpxssz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj202588.top/Article/details/gtrrzpzgze.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gtspnnkzoh.html

df -h;  du -sh *
来源：http://dali.cqqwz.cn/Article/details/gtdacaphqe.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtxnqfpssr.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtuwyvfhct.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtteussozx.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtfzgvptjl.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtqxesjzww.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsclkdaie.html

[R65] 查看端口占用
来源：http://dali.316326.xyz/Article/details/gtjnyvvuyy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtcphtzsiy.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtnvthqpnb.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqmftxxp.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtfbytdoow.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gthsfsinyh.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtpaoscbcc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtepfsazna.html

[R69] 生成随机密码
来源：http://dali.shangyingyoupin.top/Article/details/gtezgivlwk.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtqxnwbiho.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtacudnxht.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtcrwymutx.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtidjrbixk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtogfzbdhi.html

[R72] 等待端口就绪
来源：http://dali.haohaochexian.top/Article/details/gtyadndqjg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtmvtjyxpa.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gtkhdgeutc.html

split -l 1000 big.log part_
来源：http://dali.hongshengwenyu.top/Article/details/gtafqxyvly.html

[R74] 批量重命名
来源：http://dali.hysaishi.cn/Article/details/gtwzwpfvvj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtqjblejwq.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtshfzygme.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtbyrwkktn.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtjqtkhgpm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gthctczkvg.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtdrydaxbd.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtipyevqrb.html

[R78] 交互式菜单
来源：http://dali.nwbrower.top/Article/details/gtzqlklcin.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtbmkwcgsu.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtxzmsgajo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.birdmap.top/Article/details/gttcxonuob.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtujiclegu.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gtauvbkwwy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gthfelqndt.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdwijxem.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjnkuafjq.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtxwqwzeip.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtwctexlbk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmuoiuxm.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtemmieusd.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtlqjlmecm.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtveakugjt.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gtttnqhcqr.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gtmtvfmhil.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtntcahvil.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gttgnkhgjz.html

strlen(s)
来源：http://dali.cashguo.top/Article/details/gtweunzpdm.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtrsrxoayl.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtuvqsrewd.html

[S07] C：数组遍历求和
来源：http://dali.snrcjt.cn/Article/details/gtjftbuizc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtfbovomyu.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtgsotwsnm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtcxnwlacn.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtfnprzjxf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zycfv.cn/Article/details/gtfnxcnzyb.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gtagcguqtr.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtjpefcdut.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gthqxxskjp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dianchejie.cn/Article/details/gtivokcqtx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtorcffexw.html

fclose(f);
来源：http://dali.9152youxi.cn/Article/details/gtqhijpnfk.html

[S12] C：写文件
来源：http://dali.gaohongyu789.top/Article/details/gtgfezjzjm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtyaojiuik.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtjnkdgcyg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtvyoqpkbm.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtwhvclhxd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtjfusfvcz.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtmtnkjrvf.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtgkddgdrc.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajfkxdpq.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsapextj.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtltvsvxyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtvxegvcpa.html

[S18] C：命令行参数
来源：http://dali.xuanzx.com/Article/details/gtkglorsld.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtxbshhqsf.html

[S19] C：快速排序
来源：http://dali.gaohongyu789.top/Article/details/gtgiokudth.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtshqabnuv.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtkdzxdkbj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gtpiznsjoe.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtkiqszykm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aizwys.cn/Article/details/gtbaropvki.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtnqsvieti.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtezvqbtqh.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtatbqbpwk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtnvsysoke.html

[S24] C：获取本地时间
来源：http://dali.9152youxi.cn/Article/details/gthpzmoayv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aizwys.cn/Article/details/gttclurlfl.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtuivuwpkr.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtiqumovix.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcraguxg.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtgncpespo.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gtxjkbhcvu.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtczqlnfvn.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gtddvkjulk.html

static int counter = 0;
来源：http://dali.sufxvd.cn/Article/details/gtfxkwvwjx.html

[S29] C：变参函数
来源：http://dali.hywenlv.cn/Article/details/gtatlhriuc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtftvaxgfh.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtszgfkuln.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtwotwlqgj.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gtxvktwwwe.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtvpinnysj.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtgaiaxfud.html


<!-- 参考信息 -->