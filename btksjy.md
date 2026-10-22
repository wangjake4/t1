代发 wailian999

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtbstskxsc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtjzogsrlb.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gttcxeqiok.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtjefogzbl.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtjgglfazm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gthrqtzpbr.html

[Q64] 提交事务
来源：http://dali.dianchejie.cn/Article/details/gtlboegdpj.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtzokmjjgj.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtltkseotf.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtrlmwbwli.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtudrfbjdy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gtirciqdss.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gtdydaogaz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtbndqalud.html

[Q68] 保存点
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnckokuqx.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtuxsnopfr.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtsjodtnip.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtefxncdzp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtvznjwchg.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gthuhtbzae.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gtcbtfekrw.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtyyhenant.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtjicntrkm.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtfwzhjfbp.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjfrwlmzh.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtcqvykrji.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtubjsrxqn.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtjltzxonc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtgekmbcna.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtokurpvnm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtgddtbncg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtszokrtrq.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtoxjndhve.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtycsyvxky.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtvyktiqag.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daria6918.cn/Article/details/gtsyteberk.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtjdsuedys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtiiqjvwuh.html

[Q79] 字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtfxhbvvao.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yangfankeji.com/Article/details/gtpsmohtpb.html

[Q80] 字符串截取
来源：http://dali.snrcjt.cn/Article/details/gtqwzulyiy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtktenujee.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtlircpthk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwxdvbkyx.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtarbinvbb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtsvibiill.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtapdlmtcg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjowvxwzm.html

[Q84] 去除首尾空格
来源：http://dali.kuanghao11.cn/Article/details/gtymyesosv.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtztqtsqnx.html

[Q85] 数值取整
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqrdajsx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.birdmap.top/Article/details/gthjytdmxm.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtpjnmzztp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gtuqctqcec.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gthamskkdn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtjocepgjr.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtovprarcu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenzaomai.com/Article/details/gtdwadbqhe.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtseanqvja.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtrzmwbkff.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtfkobuked.html

[Q90] 生成序号列
来源：http://dali.jlsjyb.cn/Article/details/gtkjxbthay.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtrzvxdcni.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyqlmrajw.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtkcomeqma.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjdjowswn.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gtcpykigly.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtcfvjnpkn.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gtlngpwkya.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtvvszrfdb.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtnvicecot.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gtcbbzlqri.html

readonly PI=3.14
来源：http://dali.gotoacloud.top/Article/details/gtlulpkmlc.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtnwkvyskw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtbiilumey.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtywiconud.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtiteaixru.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gtbsgxqicw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpwdsosa.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtbmmjtthm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqkxyioz.html

[R08] 数值比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtigcasksm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xylfe.cn/Article/details/gtrtyugiqa.html

[R09] 字符串比较
来源：http://dali.feifeiyinyue.top/Article/details/gtggjabhrr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuanzhike.top/Article/details/gtzxotgubw.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtlrtjjvrk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtesfojhxh.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gtfzrxeptu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gtndgvsrxp.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gturplwlmt.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtqllfonrq.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtsrrvwnvm.html

esac
来源：http://dali.guannengcc.top/Article/details/gtsxlcezfi.html

[R12] for 遍历文件
来源：http://dali.hysaishi.cn/Article/details/gtkfofgdxb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtfqhwjagr.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtylkzebsj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtydmhveem.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtfndazvam.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtjdplvuwy.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtjlvrudza.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gthstupxhm.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtkxchhten.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtayzvrjep.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gtunpdpojt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cheryme.top/Article/details/gtbpqxrzii.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtvfikzuoh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sxryk.cn/Article/details/gtazzmhydu.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtdbyjbahs.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtsjfdlcvd.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtznhmrepa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yanxiufei.cn/Article/details/gthdwjfcrz.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gtwlkzokeo.html

echo "${#s}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkukajhz.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtajazixip.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvprtsset.html

[R23] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtoqbefswt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gtlkvwvqnj.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtxydhjbyx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtdfycsyzn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtzcvddtiq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmptzwujf.html

[R26] 命令替换
来源：http://dali.aibaodan.cn/Article/details/gtzsyrqjdx.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtqjpgnrkp.html

[R27] 算术展开
来源：http://dali.ehwqpu.com/Article/details/gtwxrasrap.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gttsmrtxya.html

[R28] 浮点运算
来源：http://dali.tianlin.xyz/Article/details/gtovpkyjfz.html

echo "scale=2; 10/3" | bc
来源：http://dali.gaohongyu789.top/Article/details/gtlaogklik.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtxjoklvlo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtkzgvuyhs.html

[R30] 函数返回状态码
来源：http://dali.redwolf501.top/Article/details/gtuuohfdtm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtavjgqtkr.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtmdokhmmg.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gtyifdbvpm.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtwdylptol.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtyqcyarxo.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtebdctsxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtueydlnzl.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gtrzemxcpe.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gtygdywziv.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gtvrqsdmcg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtkugykons.html

[R36] 并发执行多个任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzcyryrd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yueranfly.top/Article/details/gtcopcqtva.html

[R37] 把输出赋给变量
来源：http://dali.zycfv.cn/Article/details/gtqqdoumqg.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtjtmvguee.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtzswvlwsm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtldpvipnb.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtqdmpwpay.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtbrmrywdu.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtpcafrnht.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtldomqwti.html

[R41] 丢弃输出
来源：http://dali.hysaishi.cn/Article/details/gtnqalbytg.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtwbanucyu.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gtrulkwbbm.html

wc -l < a.txt
来源：http://dali.jyoumei.cn/Article/details/gtgllkbwvo.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gtiehusjsw.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtuhkyrrth.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtyivfqsqo.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvghaewz.html

[R45] 批量删除
来源：http://dali.xuanzx.com/Article/details/gtsulukmof.html

find . -name "*.tmp" -delete
来源：http://dali.nanxuanxn.top/Article/details/gtntgvdyyl.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtltbrvmle.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtcffroiur.html

[R47] sed 单行替换
来源：http://dali.cucudq.cn/Article/details/gteapntpgk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtnqsdgxiu.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtcubrhqfd.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtymngsjzb.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtnjkmlpot.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gttoqhguxy.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gtroyarswy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gtmtbdowjh.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtffburqjo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shangyingyoupin.top/Article/details/gtsczdlqhj.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gthcetapqi.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtpibrujmu.html

[R53] 查看文件头与实时尾
来源：http://dali.chenzaomai.com/Article/details/gtziaagips.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gtnqlldbld.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtssspokie.html

diff a.txt b.txt
来源：http://dali.yanxiufei.cn/Article/details/gtwkigluht.html

[R55] 压缩与解压
来源：http://dali.hammf.cn/Article/details/gtgyevtuwf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtzmvdnreq.html

[R56] 远程拷贝
来源：http://dali.tian-w.cn/Article/details/gttyodfspc.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtgsdjiyao.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gthauxcqrp.html

ssh user@host 'uptime'
来源：http://dali.zhoulong.xyz/Article/details/gtmwonsdmg.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtohnqsqkv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj20258.top/Article/details/gtuuzbtplw.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtdastequk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtehccmjqp.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaouryirn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtpjcweuig.html

[R61] 磁盘占用
来源：http://dali.wangdashe.top/Article/details/gtlkqwydqz.html

df -h;  du -sh *
来源：http://dali.jqgufenzy.top/Article/details/gtkthahdwo.html

[R62] 找最占空间的文件
来源：http://dali.ehwqpu.com/Article/details/gtexwxqaiv.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gtajhliyhd.html

[R63] 内存与进程
来源：http://dali.c1oappe.top/Article/details/gtxvvpaxkb.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtuxmtkkfb.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtnqgfipzc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtzpuqfxbk.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfxbvpzo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtkzctfybx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtmdriwqrs.html

crontab -e;  crontab -l
来源：http://dali.hongshengwenyu.top/Article/details/gtnxreccqo.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gttrtzqdxt.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gtxamyhlyu.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtixcujjbs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj202588.top/Article/details/gtvfolvqjr.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtcmdippjw.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtimytenrt.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtomwddtdg.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtcytdahga.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gttqsvvstd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtckvimiic.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtgdgxzgfm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gthzxppzpc.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gtuhuymlyr.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtzavqpadv.html

[R74] 批量重命名
来源：http://dali.mhx1999.top/Article/details/gtvzndsvsc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtqlwbubbx.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gtcuhkcdyw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtyuusrosq.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtcezxfeot.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtiltievks.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtqlrhunjj.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtilstqved.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtcccmfify.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuetiantiany.cn/Article/details/gtvvsdntra.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtrugxgksd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gtduhgaiyi.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtgvtfhifc.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtzjiziwud.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbambexux.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gteevdvbbo.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtckooxnvu.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtebghlmgn.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtvmpyutfw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtlsflpfyh.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtlgyixdkf.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenlongwang.top/Article/details/gthttqhrvt.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtvcvywcom.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtsifzsmzc.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtkzidzonv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtrjdehgmi.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gtkgxjdfmv.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtpxqsvfez.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtpqmrotdr.html

strcmp(a, b) == 0
来源：http://dali.hnxiangtu.top/Article/details/gttqmklxka.html

[S07] C：数组遍历求和
来源：http://dali.xylfe.cn/Article/details/gtqgcmzcdh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtoubxjqkb.html

[S08] C：动态内存分配与释放
来源：http://dali.sufxvd.cn/Article/details/gtfwvgrhgw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtmokccgls.html

[S09] C：结构体定义与初始化
来源：http://dali.yuxming.cn/Article/details/gtajmbpvsx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258888.top/Article/details/gtvlnsgkij.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtmlpdnkoq.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtcsdtptvp.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtzesealcj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtjjjmpcrr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtwzcgpzel.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gtrksmamij.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtvsozpslb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtvpfujkgk.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtmrqowiaq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gtnjolzcfj.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtzufuoulo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangshuangyany.cn/Article/details/gtuiguebvn.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtqwlxyyzy.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtygxicina.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtxammdikz.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtrslcpuws.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gthgqfpara.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtdufbxkqm.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtgduzbsrl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtwlkgvckj.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbehqlsql.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gttbhdijdk.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtybbgtovt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtlyfwldgj.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gttzzukrgq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shzxlz.cn/Article/details/gtzidxaeny.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtvcfvvdnh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.birdmap.top/Article/details/gtyibnuvxc.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtpotqugbp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xinyue.icu/Article/details/gtmgmeriol.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gtmybtunlg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtbimflitq.html

[S25] C：内存拷贝
来源：http://dali.jianghu66.top/Article/details/gtmazrudgg.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtwgiaxypo.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtsvhagwkh.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtulvysozj.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtczhcgcvb.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gthixgfmnu.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtqecblwdi.html

static int counter = 0;
来源：http://dali.bjfxy.top/Article/details/gtykwkcmpz.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gthcpbpnnf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtlvouqwqm.html

[S30] C：头文件保护
来源：http://dali.0kj1m.cn/Article/details/gtteyxuuyi.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtjigkxqjd.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gtaxozfeao.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtocskfnll.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtecxmewmj.html


<!-- 参考信息 -->