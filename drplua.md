代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtutdlbxqh.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtamlkukom.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtwqqvmpwc.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtqmqjyzsn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtoqeuavwd.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gtydcxzaek.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtmmixndcw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtjybaiiaf.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtcqsvexfj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gticixuybc.html

[Q62] 分组占比
来源：http://dali.nanxinkj.top/Article/details/gteoakizwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtvtandtve.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdohwlzvs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieyfwccu.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gttuzeyfcg.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtvuijxolb.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtggouqfzh.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtzctqtlek.html

[Q66] 行锁查询
来源：http://dali.yongpay.top/Article/details/gtyczgcmvl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtlriagsez.html

[Q67] 设置隔离级别
来源：http://dali.dashuyun.cn/Article/details/gtgeuwumwk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtkqocntde.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtzpbrtmsj.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtoralcjfk.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gtzmbtaakr.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtjztozjgq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gtaasnvdcw.html

[Q70] 更新统计信息
来源：http://dali.yuxming.cn/Article/details/gtlxpkfhlx.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtferbsued.html

[Q71] 查看建表语句
来源：http://dali.feifeiyinyue.top/Article/details/gtjsmcnvcf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ydzc1.top/Article/details/gtudzdorst.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gttokcaqjr.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtfulapntd.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtewrpdnzi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtoschwkho.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtmqyuwlvv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtkrkshlqf.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtectbhguj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtwqaaaylm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtxrhyrluo.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtiwwybwpk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtfqxmkgjb.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gttvvbuppo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.9152youxi.cn/Article/details/gtxnqtaxtd.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtdmbpgeei.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjnhsnyl.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtptbqmxgm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtxzeqeuxv.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtfoegvivh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtfwpmftdq.html

[Q81] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtwbpvirku.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtveaetyuy.html

[Q82] 字符长度与字节长度
来源：http://dali.jqgufenzy.top/Article/details/gtmkqmgasc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtoqqvoxna.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtvzvrlkwr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtuaduxvvv.html

[Q84] 去除首尾空格
来源：http://dali.aibaodan.cn/Article/details/gtfshkxbxr.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtartghmyf.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtvzclxqfs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gtyurdoeja.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtyntgmlfh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtqkzncubo.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gttuammzbj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtdvcawfma.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtkyswodnb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtbkgclwzy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtlnyspnra.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtjnsgdpph.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gtwxbvkxrd.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtekdtkqhy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtewpgvfjh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnwpphwpl.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gtiscgxihs.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdruuocib.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtaysihlpo.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtjrfijplx.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtpeyomkmy.html

[R02] 变量赋值与使用
来源：http://dali.gotoacloud.top/Article/details/gtepbojzgn.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtjaaawjxc.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtyfnweuin.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtgjtranht.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtioiqmlsz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtriocdynd.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtorzlmijh.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gtkjfsjasf.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtbssglhws.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtulavyvrw.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtedduxuex.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtenkufzoq.html

[R08] 数值比较
来源：http://dali.yuanzhike.top/Article/details/gtdvmehhlz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtkihkqasw.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtodmatvhw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgoqxaiv.html

[R10] 正则匹配
来源：http://dali.haohaochexian.top/Article/details/gtjxsrlbwg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gtanrfifzv.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtygyspwdy.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtobumglxt.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtyfeejkjl.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtwvlidmav.html

*)     echo "未知命令" ;;
来源：http://dali.chenlongwang.top/Article/details/gtrbkcykfv.html

esac
来源：http://dali.shanyushiyangtech.top/Article/details/gtemqsotgh.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtabdsfwfg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtvrvfabsw.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmhtrtli.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtrzzsicmf.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gtcuhbtfav.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtbsjtegfo.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtjsxuphep.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtkszyemwf.html

[R16] until 等待条件
来源：http://dali.ppjwa.cn/Article/details/gtobqdwbvh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yuanzhike.top/Article/details/gtoappfslb.html

[R17] 数组定义与取值
来源：http://dali.hongshengwenyu.top/Article/details/gtuoumyejx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cashguo.top/Article/details/gtxfezmcwe.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gtfvztongf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gtjlnmsffh.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtidjfcohp.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gtjarmzvdq.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtgcxpwbbh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtmnvuwzhk.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtdazgnfwh.html

echo "${#s}"
来源：http://dali.jianghu66.top/Article/details/gtpulkhhuy.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtjwxhxevm.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtjvwdkosj.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtlthmphre.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtzbkbbihj.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gteoefjmmr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gtvcbwwzbl.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtatzvzhto.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gthwanmuib.html

[R26] 命令替换
来源：http://dali.yvedp.cn/Article/details/gtlltdnxfk.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gtcexevkiq.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gtpprawjzo.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtppsqnggo.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gtsudqmxxq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtvakgjxpc.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtqwtbtqcb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpewtgeud.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtdhqydpig.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shangyingyoupin.top/Article/details/gtyzintnrq.html

[R31] 局部变量
来源：http://dali.cdnleiting.top/Article/details/gtfsgrrlwq.html

f() { local x=1; echo "$x"; }
来源：http://dali.daria6918.cn/Article/details/gtyfaxwlwf.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtpbqmrxha.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtnxiygtmc.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtdnabaiwc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtiwdekfcv.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gtwycvvlyg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gteapgtqag.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtqgyggqgu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtdoafctia.html

[R36] 并发执行多个任务
来源：http://dali.sufxvd.cn/Article/details/gtondojlkz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuetiantiany.cn/Article/details/gtivkatnie.html

[R37] 把输出赋给变量
来源：http://dali.chenjidiqi.icu/Article/details/gtpssyaaom.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtozrwhfzw.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gtorwavwfq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.vqdsnc.cn/Article/details/gtxugovesq.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gtywbgtnpp.html

cmd > out.log 2>&1
来源：http://dali.hnqzz.top/Article/details/gtfbbbebwq.html

[R40] 追加写日志
来源：http://dali.sweek.top/Article/details/gtlovbrsim.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtcfmcptjk.html

[R41] 丢弃输出
来源：http://dali.tian-w.cn/Article/details/gtrbtvardo.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gttnvfdbxz.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtgigqpuia.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gtsgijiwip.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtiszsdlnt.html

find . -name "*.log" -type f
来源：http://dali.jiagoushi.top/Article/details/gtrcylyvvv.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtvarnqhco.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gtiaitkmyl.html

[R45] 批量删除
来源：http://dali.ppjwa.cn/Article/details/gtkzawsyno.html

find . -name "*.tmp" -delete
来源：http://dali.zhiwuduotai.top/Article/details/gtkpdhslbe.html

[R46] 递归替换文件内容
来源：http://dali.meibo888.top/Article/details/gtkphhkxki.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtmnwrjsli.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiyhhknt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtvllecsdg.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtuonairet.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtmdkasmtk.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtvyejtoqv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtwqjlxwdb.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gteoeezvri.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtffknhtww.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtfrgdrkdx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gttgohurib.html

[R52] 统计行数
来源：http://dali.316326.xyz/Article/details/gtkdrqhahc.html

wc -l a.txt
来源：http://dali.c1oappe.top/Article/details/gtsryepncu.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtkgxmmusk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtdcokurkj.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gthibjemni.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtavfwrgea.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtbxuvengs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtrdckzvho.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gthxbudfkt.html

scp file user@host:/path/
来源：http://dali.ivvv.top/Article/details/gtgwqqrmrw.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtvhwcqzwr.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtnkprwepr.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtsnzwfjhk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtixfzsudb.html

[R59] 发 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gthqnpgngo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigufen.top/Article/details/gtwtpztebb.html

[R60] 只看 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtvvggbeyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cqqwz.cn/Article/details/gtvhthzwsl.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gtrqevabxb.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtuwbifpws.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtsfphkapf.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gteadvrzbz.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtqdypzchc.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtobwyhdgh.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtizikftik.html

kill -9 $(pgrep -f app.py)
来源：http://dali.wangdashe.top/Article/details/gteevtdkbd.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtqesykmht.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtnqieiqsi.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtburejjns.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtacxsdkly.html

[R67] 生成随机十六进制串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgwvhgvi.html

openssl rand -hex 16
来源：http://dali.kuanghao11.cn/Article/details/gtpivftxqr.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtnxdcnkah.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtumtlqdxp.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtsgzxwnxc.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtpeywohvn.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtviufncqu.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtazmiokil.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtddndbnkj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtfkhfkznh.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtqeywjsdq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtbbfukskv.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtkrxasjum.html

split -l 1000 big.log part_
来源：http://dali.cdnleiting.top/Article/details/gtdwifymoy.html

[R74] 批量重命名
来源：http://dali.quarkkingdee.top/Article/details/gtocupjpze.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuanzx.com/Article/details/gtamgkeurr.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtohqiaqzk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gthubeaeha.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiisvkxv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtfbixsirc.html

[R77] 读取用户输入
来源：http://dali.zhiwuduotai.top/Article/details/gtwvplxjtn.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtephrioie.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gtjhdygiby.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtgknkhvkw.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtbiqxnlwr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gtyxccmccw.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gteidhmput.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gtfeebmted.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzmjpzirn.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gttipftqex.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtymgydcwb.html

[S01] C：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbhbfgaja.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtdxdhgvui.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtpllvbspq.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtagheclud.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtfgdpamko.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtkmirlqpj.html

int x; scanf("%d", &x);
来源：http://dali.jianghu66.top/Article/details/gtfsgphoqa.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtbcwatjwm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtwkpjbsyh.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gtunlmyxlh.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtidetpovw.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gtahlfqrox.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtzsagdodg.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtuiltvqug.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yvedp.cn/Article/details/gthikzjkki.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtigfmzopj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtuhpzfjcf.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gterkctmiu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gtqnjadxuh.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gtueedvzmr.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gtqodztiva.html

[S11] C：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtxoziddtp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtunmdbcgy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtilfuokfh.html

fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtmcammnbi.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjylmfebl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtfdhatnet.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gtnjgxcdij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtjvfpopuk.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtqjddqkbo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gtsqxtfccv.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtdqsrwhcp.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gtaqgxvdcy.html

[S16] C：位操作置位
来源：http://dali.xuetiantiany.cn/Article/details/gtenpvoumo.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtrnfnsoxe.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtqmwmsegy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtlijtwwhc.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtlfwwzmuu.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtabuatqll.html

[S19] C：快速排序
来源：http://dali.havefunace.top/Article/details/gtdopwyhxb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gthcagdyyk.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gtnzwnsvcs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtizmojopo.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtgyfzzsrk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtarjnltzs.html

[S22] C：字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtmwofelrm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtcdifwslr.html

[S23] C：随机数
来源：http://dali.jinqigfzy.top/Article/details/gtazgvlzcu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtgayszpha.html

[S24] C：获取本地时间
来源：http://dali.zhengqikj.top/Article/details/gtcwarrkcb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtusfjdajd.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtzrgagwyj.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gtnpkoaeoa.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtgtuahjnl.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtnjlujmjb.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtvrztlqht.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtbluydecu.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtqktccwiw.html


<!-- 参考信息 -->