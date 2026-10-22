代发 wailian999

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtlpkfkeve.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtjyqmikwg.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtfiuuiwdg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtpqjwnnpp.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gthauamrpv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gthzgmqgqf.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtojayipry.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtpftigwpw.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gthbxdrfut.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtonydqrmc.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gtacdjkvnf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtqcrgkbhp.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gtzqpvjvlu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtxdbsvllh.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtxanaodet.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtzgfrimqa.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtumovhcan.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtwjphmqhx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtxecebpfu.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtlofmlrsy.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtyfvaxryf.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtoxsmtere.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guowangkeji.top/Article/details/gtyrpgwwor.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtwayztszh.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtiqwvsdsj.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtsdmndmxe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtwqvcotuk.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gtgpzigiik.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.svipenyu.cn/Article/details/gtooofpzcs.html

[Q75] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtjfaqioeb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtpnmzljpo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtpzbcyadw.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtebfzlpxr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gzhubu.top/Article/details/gtkfcqgkfn.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gtxfcslxul.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gttwfgatrs.html

[Q78] 当前时间
来源：http://dali.sweek.top/Article/details/gtigucdfei.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gtcwgjfegq.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcwckloh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtncbhalau.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gtzrmydlus.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtqpvzjhpn.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjudtymyl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gttulovwso.html

[Q82] 字符长度与字节长度
来源：http://dali.snrcjt.cn/Article/details/gtwvjehabq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtezljmrpo.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtwveglacu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtxqiartat.html

[Q84] 去除首尾空格
来源：http://dali.0kj1m.cn/Article/details/gtvoqgnfpj.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtwbwhydxi.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtgpzgcews.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gthlffenie.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gttexyggdw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtugwkdtox.html

[Q87] JSON 字段做条件
来源：http://dali.tianlin.xyz/Article/details/gtfedqxspw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sweek.top/Article/details/gtalogffjj.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtasuzcaho.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jqgufenzy.top/Article/details/gtpahjlgov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwiphebbt.html

[Q89] 判断表是否存在
来源：http://dali.cucudq.cn/Article/details/gtmiemzdge.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtrjizuhgs.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gtovuupwlc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtrhrwinzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdkveamei.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgwyrbfs.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtnhyeywsm.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtcirsyjcc.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtcwogwcrm.html

set -euo pipefail
来源：http://dali.yj20258888.top/Article/details/gticdrucuk.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtxbvrripz.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtuymhenjy.html

[R03] 只读变量
来源：http://dali.yvedp.cn/Article/details/gttmkzpoiw.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtjiftgueh.html

[R04] 位置参数
来源：http://dali.snrcjt.cn/Article/details/gtqnoweeqt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuubodiqc.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gterhyurba.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtpqsmzbzq.html

[R06] 判断命令是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnzmfzkk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gttdzktmgm.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gtnaqkezpe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtlifzosnk.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtsjxveptx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gtwynxcisx.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtogjztfnk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtqalcjtdd.html

[R10] 正则匹配
来源：http://dali.tanke756.top/Article/details/gtbxicrycz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gtjezgvhri.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtdlnoyhom.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gthacqwobd.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtffopkjnd.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkkvolpt.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtfflejzwu.html

esac
来源：http://dali.mhx1999.top/Article/details/gthdnkwebm.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gthujgfzma.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtkczhvplb.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtlsuneyqr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtwcnsubxv.html

[R14] C 风格 for
来源：http://dali.haohaochexian.top/Article/details/gtfnfzcvhi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gtsalofwin.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtdvnbjofs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtrlzoivfc.html

[R16] until 等待条件
来源：http://dali.jlsjyb.cn/Article/details/gtdmsohres.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtwoqczldl.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtirwhbjbe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrdwonjm.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gtabdsnvdq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gtviwknije.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtdoumwhjy.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gtcmbsholp.html

[R20] 关联数组（字典）
来源：http://dali.sxryk.cn/Article/details/gtdpfmnoix.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ydzc1.top/Article/details/gtrdcuqspm.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtznwkurkg.html

echo "${#s}"
来源：http://dali.9152youxi.cn/Article/details/gtsiriwkcw.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtfpessfrm.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gthifywhdm.html

[R23] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtmdcscmlm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.9152youxi.cn/Article/details/gtzpygzqrd.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtomomsgtp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigfzy.top/Article/details/gtkjggogtw.html

[R25] 去后缀 / 去前缀
来源：http://dali.snrcjt.cn/Article/details/gtoflewwqp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbhrymlw.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gtlcsvksbv.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtlwtfdhui.html

[R27] 算术展开
来源：http://dali.yj20258888.top/Article/details/gtyqfusrkd.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtucnuoene.html

[R28] 浮点运算
来源：http://dali.sysykeji.top/Article/details/gtbqxznhvv.html

echo "scale=2; 10/3" | bc
来源：http://dali.hysaishi.cn/Article/details/gtwukiofyp.html

[R29] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvcquoxk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.316326.xyz/Article/details/gtoieyvnji.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtwqvvghjg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtgbpferhu.html

[R31] 局部变量
来源：http://dali.yj202588.top/Article/details/gtzgsqosae.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtdqvpocxq.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gtkdqjhfus.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkqvzglk.html

[R33] 捕获错误并提示行号
来源：http://dali.gaohongyu789.top/Article/details/gtmmrgkwuy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtmavuqfok.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtegrikowj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gttanaixdi.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gtkjfqqylq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gttqqxwtwq.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gtarucurkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtsmofmduy.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtoanumkvi.html

files=$(ls -1)
来源：http://dali.chenjidiqi.icu/Article/details/gtlqncazru.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gtueijctbp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fzhhl.top/Article/details/gtxbdrtkvw.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtpxyxhosq.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtcsfdjnwe.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtpwgzvagl.html

echo "log" >> out.log
来源：http://dali.nanxuanxn.top/Article/details/gtgoqljabq.html

[R41] 丢弃输出
来源：http://dali.fengsongda.top/Article/details/gtdixjdrku.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtnszvkseg.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtzrbvrnyw.html

wc -l < a.txt
来源：http://dali.tianlin.xyz/Article/details/gtfqxhutmn.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtweajdylc.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtwuhaqlsh.html

[R44] 按修改时间查找
来源：http://dali.ydzc1.top/Article/details/gtqiyezwew.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtolcrczyf.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtzihqfywo.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtxvabtkxn.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gtynycuefr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtalgxeyxg.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtdpyuuoqo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtvrindrha.html

[R48] awk 取指定列
来源：http://dali.daxiang520.top/Article/details/gtdvdpnvkd.html

awk '{print $1, $3}' a.txt
来源：http://dali.jianghu66.top/Article/details/gtumpyycuf.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtapnerjvv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gttokywolh.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtueixbrix.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtaaydvyyx.html

[R51] 排序去重取前几
来源：http://dali.sweek.top/Article/details/gthcpnsgig.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtkqcsdjwm.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtqdrymzuw.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtsuvkxybm.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gttemvjtsi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtghpzlezm.html

[R54] 比较两个文件
来源：http://dali.zycfv.cn/Article/details/gtuhcxxfdq.html

diff a.txt b.txt
来源：http://dali.hammf.cn/Article/details/gtxvhfkysu.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtxpbfbgfg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtauunzisj.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtuoptymej.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtsgehebld.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gttlxizjhl.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtaepmbsrs.html

[R58] 下载文件
来源：http://dali.xziqi.cn/Article/details/gtpxzppwtu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gtshzhnsgg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtshvqygrm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtlgfpuvpo.html

[R60] 只看 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtyfbmljqd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtzsrtvrus.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtynaabvrl.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtbupfeqsj.html

[R62] 找最占空间的文件
来源：http://dali.yanxiufei.cn/Article/details/gtaiesgtya.html

du -ah . | sort -rh | head -10
来源：http://dali.meibo888.top/Article/details/gteaorixvd.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtgntgoldu.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtcqqcrpnn.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtdeulktjb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtspszxiiu.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gthwkykxjv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.havefunace.top/Article/details/gtoasjamlg.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtostfycwn.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gtqztuyrmd.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtwflvwplk.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtyctzplqh.html

[R68] 计算文件校验值
来源：http://dali.jinqigfzy.top/Article/details/gtelfjdtdl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtezhyefna.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtfgcbmzwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gthbszepns.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtthanobur.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtsxojuoaa.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gtnkvyjdic.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.andypj.xyz/Article/details/gtvpbwbite.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtfgjpnwvk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtsmhudzhx.html

[R73] 分割大日志
来源：http://dali.sysykeji.top/Article/details/gtsfuuxlrt.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtqspanexf.html

[R74] 批量重命名
来源：http://dali.hfpthk.cn/Article/details/gtodeohmrz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtjolwivmd.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gtbtwtaktp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtaecywzlt.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gtdhgkgfrl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gteeeektnu.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtwingztnh.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtzgifteiz.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtbbfkgahl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nanxinkj.top/Article/details/gteauoaeqf.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtaxylohvl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.bjfxy.top/Article/details/gteaeafhvo.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtzrxikmox.html

time ./run.sh
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkjwzmuh.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtflkiovrz.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtnxedebyl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqcbqblty.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtztutvzrn.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulroydey.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtjkaerpjq.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtbykcikwo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtrzwsxfzf.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtunxtmuhm.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtkeckbynu.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtlxmziveh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwdknvxh.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gthmqqjdjr.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtpewduzfh.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtdfkthane.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsslblvf.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtuadaybts.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtsrjvckox.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaolqdgvs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtokfqflqz.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtsixmrhsn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yongpay.top/Article/details/gthugsdkcg.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gtvvswbsrx.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtxhhqisfi.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjloymcem.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtqqkjdors.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtgnwwpdzm.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gttnjvzoon.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtohnoukbd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtwxeaxqxl.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtxbpwfvve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tianlin.xyz/Article/details/gtakboqahk.html

[S14] C：枚举
来源：http://dali.hnqzz.top/Article/details/gtyzveuqjn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtzfdlqzii.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtrtrifbrg.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtefsbfhee.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtlrbklprj.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtuajkvldy.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtewuxlkgi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtlmplcvqo.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtxjfducqb.html

int main(int argc, char **argv)
来源：http://dali.zhixingplan.top/Article/details/gtgxgnfwwj.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gthqqwioju.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daxiang520.top/Article/details/gtlpihzycf.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gttkqsgwry.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtpuumxkvb.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtqtcorziz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtskgfmcay.html

[S22] C：字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtqelafkaw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.dashuyun.cn/Article/details/gtlgvxedfo.html

[S23] C：随机数
来源：http://dali.daria6918.cn/Article/details/gtnatqjmks.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gtrbludiwe.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtyujomxuz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtjtpibbcc.html

[S25] C：内存拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoviipwc.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtpifdjjjk.html

[S26] C：内存清零
来源：http://dali.hammf.cn/Article/details/gtjbkoaqit.html

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gtgdhlpzpr.html

[S27] C：定义常量
来源：http://dali.quarkkingdee.top/Article/details/gtffltwbar.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtabqiynzf.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtasgxdyqy.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtgirywdch.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtsnsvcpmr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gtnzfoosra.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtgcxlmxct.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gteuhtrpre.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtchvsclrr.html

#endif
来源：http://dali.hongshengwenyu.top/Article/details/gtajgjjjpq.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtzkiweznz.html


<!-- 参考信息 -->