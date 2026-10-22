代发 wailian999

[Q61] 移动平均
来源：http://dali.tianlin.xyz/Article/details/gtriwirkqb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtcbukprgm.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtmxfbkypg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtyzgqyapc.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtsrhyovlz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gteniwjpqf.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtibxsedgz.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtyekzdhni.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gtyisowqsk.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtoagybynb.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtmswonnof.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtdxolukhz.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gttkjpckod.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtgqgdwful.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtejgyvgiv.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtmyzgmmuq.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtrohhltgs.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gttfkwobqc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwwiubyk.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtfasikrix.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtmatihdiy.html

[Q71] 查看建表语句
来源：http://dali.316326.xyz/Article/details/gtainbcxpj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtltscjoev.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtlzioembv.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsrcfsfgy.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtqclfoegj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gthtyhazec.html

[Q74] 强制使用索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuuipqwd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtitbbttcx.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtuddnhaby.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtydecaggx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gtfzjdvytr.html

[Q76] 按天统计
来源：http://dali.hywenlv.cn/Article/details/gtoahcarrj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtqrmfltta.html

[Q77] 时间加减
来源：http://dali.yj20258.top/Article/details/gtsyhntjnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shzxlz.cn/Article/details/gtmiuwutgu.html

[Q78] 当前时间
来源：http://dali.daria6918.cn/Article/details/gtyfmiveua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtqjpiyexf.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtuhgqlcgs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtesyysusq.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gthcwdpoqu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtnxeuyiff.html

[Q81] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtnlylyxcq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtigyeoiyq.html

[Q82] 字符长度与字节长度
来源：http://dali.hfpthk.cn/Article/details/gtobeejkks.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkxcfpxdw.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtiojctopm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtwbpauqda.html

[Q84] 去除首尾空格
来源：http://dali.ybcxt.top/Article/details/gtnmywpeeg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtkwsvepfk.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtcugtgmcr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xziqi.cn/Article/details/gtwuwpulcg.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtmaoxzoax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.iojbl.cn/Article/details/gtggktyhjj.html

[Q87] JSON 字段做条件
来源：http://dali.tian-w.cn/Article/details/gtkzsdudfr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtajqfbimf.html

[Q88] 行转列（条件聚合）
来源：http://dali.sufxvd.cn/Article/details/gtoirsiifu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtwjqwknhw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtcmouemmi.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtfogpjvye.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtotqrokta.html

[Q90] 生成序号列
来源：http://dali.cashguo.top/Article/details/gttwxombcz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtfsiljwvg.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfwmujzyb.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtoysjiiue.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpemfqtya.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gtjfbjxvxe.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gthpsnntro.html

set -euo pipefail
来源：http://dali.ehwqpu.com/Article/details/gttgfjkgmj.html

[R02] 变量赋值与使用
来源：http://dali.xylfe.cn/Article/details/gtzpucyghu.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtkkcsifis.html

[R03] 只读变量
来源：http://dali.daria6918.cn/Article/details/gtonbslzwi.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtsaipyxqv.html

[R04] 位置参数
来源：http://dali.ehwqpu.com/Article/details/gtfaoptobt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtgbpskrzn.html

[R05] 参数默认值
来源：http://dali.cucudq.cn/Article/details/gtcdqwdhcw.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtwbfqurnk.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gttdyhuxve.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtshlmrlwg.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gtruotemly.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtrmhjcyjv.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtevllvorn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zdqjudy.top/Article/details/gtqwzmqtzd.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtbcyyebcl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtkjlnkpud.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtenkesdbf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtwfmwtouz.html

[R11] case 多分支
来源：http://dali.vqdsnc.cn/Article/details/gtinbgalgt.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtqsydqjaw.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtbpjngbde.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtgyxndplv.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gtqaggyiym.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtkmztnkbb.html

[R12] for 遍历文件
来源：http://dali.tianlin.xyz/Article/details/gtlplzgrjj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtevanuyou.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtxnycfvxk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gttqaslzty.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gttchijgrh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtgfojmbtj.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtdagsdazb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsdljbrf.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gtsqarapdy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gthruzxmwv.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gtilqekduk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gtgwqipwtz.html

[R18] 遍历数组
来源：http://dali.svipenyu.cn/Article/details/gtthuocvjg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xylfe.cn/Article/details/gtxllufejj.html

[R19] 数组长度
来源：http://dali.yonumen.top/Article/details/gtxmbwiekr.html

echo "${#arr[@]}"
来源：http://dali.ivvv.top/Article/details/gtnskplqrn.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gthvqqipvl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgfqretu.html

[R21] 字符串长度
来源：http://dali.xinyue.icu/Article/details/gttdtqnjfk.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzegcovqp.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gttxqbxavr.html

echo "${s:0:5}"
来源：http://dali.smart0.xyz/Article/details/gthcdtxmgf.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gttbxisfvv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gtykzhyasv.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtihlhipiy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtofnfwmmp.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtwrooizyz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gtqedsjmjg.html

[R26] 命令替换
来源：http://dali.yueranfly.top/Article/details/gtjlmxjgdx.html

now=$(date +%F); echo "$now"
来源：http://dali.snrcjt.cn/Article/details/gtnkqxlvgw.html

[R27] 算术展开
来源：http://dali.svipenyu.cn/Article/details/gtfrguaoqo.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtvngrgflx.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gteqakzjqz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtvlbrxmxu.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtsdjjoxls.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gtojqvhxai.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtrjtpvvzb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gtdpqphxcy.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtfvfconwv.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtwqkrxkih.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtsbaxzmlo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtxkvyhodm.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfoonzsn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtogqfcfxw.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfhmjyqu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtshklqzrc.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtpnsqvrzu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtizluxxtq.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtwtnfsxlp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gtcvwgoydi.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtmyrkveuk.html

files=$(ls -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtnmtsswws.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtzzqbtnhw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtezleduju.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtcduwrbxv.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtunwepwuw.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtvhemkawr.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gtufedgisj.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gticcznobf.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtyfflhiag.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhdpnzbq.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtizqzuofi.html

[R43] 按名字查找文件
来源：http://dali.hammf.cn/Article/details/gtwtqmeszo.html

find . -name "*.log" -type f
来源：http://dali.jqgufenzy.top/Article/details/gtnmgpbucr.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtizbnuzlu.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtromwvzpa.html

[R45] 批量删除
来源：http://dali.pengpengdd.cyou/Article/details/gteyysrfjg.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtntrcugzj.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtwkkxdgjo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtoizjwwjl.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtxkypxqvy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvwsqbou.html

[R48] awk 取指定列
来源：http://dali.jqgfzy.top/Article/details/gtppaebbig.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuasmvrhx.html

[R49] awk 带条件
来源：http://dali.chenjidiqi.icu/Article/details/gtedsyfvde.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtolptmxxr.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtrfsouslo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtekqpnmxo.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtwlhxwecy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtxuhydcnm.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtgckctxuc.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtgrrlpqmd.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gtjzjummdj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hysaishi.cn/Article/details/gtmcgvbonv.html

[R54] 比较两个文件
来源：http://dali.snrcjt.cn/Article/details/gtjiwosdwj.html

diff a.txt b.txt
来源：http://dali.xylfe.cn/Article/details/gtbapxnrhn.html

[R55] 压缩与解压
来源：http://dali.shangyingyoupin.top/Article/details/gtbffsvyfm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtyijkwqrb.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gthgtphrtc.html

scp file user@host:/path/
来源：http://dali.iojbl.cn/Article/details/gtugdyfeop.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtqemhxwln.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtjkabwpgi.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gthzskjbpy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gthefxtuxc.html

[R59] 发 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gtuyjtwllo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtgyghkuzt.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtlznbukvj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtrgvrybej.html

[R61] 磁盘占用
来源：http://dali.ppjwa.cn/Article/details/gturzcsduj.html

df -h;  du -sh *
来源：http://dali.shanyushiyangtech.top/Article/details/gtitcgoleo.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtdwuhrzbf.html

du -ah . | sort -rh | head -10
来源：http://dali.hnqzz.top/Article/details/gtqyepygql.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtolyrhygt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gteugjwdih.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtlgdemyyb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtezuxnbav.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtjsmmimet.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtagomgvyi.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtqfjypwik.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtwfgammko.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtqxhyngxl.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gttoxyxxik.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gtarrplhjy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtfzrvepmz.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtycvnsmtv.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtatparzcl.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtzxhthiwo.html

date +%s;  date -d @1700000000
来源：http://dali.gogol.net.cn/Article/details/gtgkezukko.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtsbttqquv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hongshengwenyu.top/Article/details/gtjpmrnybx.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtpxblqcxd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtwevmxphn.html

[R73] 分割大日志
来源：http://dali.0kj1m.cn/Article/details/gtmarbzmpl.html

split -l 1000 big.log part_
来源：http://dali.zdqjudy.top/Article/details/gtgrtofsbg.html

[R74] 批量重命名
来源：http://dali.cucudq.cn/Article/details/gtdmmlkwgy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtporrysgx.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtkfgxxwvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtgprgfzsw.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gtlhwppcpl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gttmgrwyyb.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtqrityfns.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtiihksymd.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtsnuwwjsg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtayjafypc.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtqzboeiho.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gthpqtuqcg.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gttsckfbgb.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtxxpjvfws.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtixrvrybi.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtubqjhoep.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtzdohzgsd.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtzmbkqiml.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtmauyxxyx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtoypfnopb.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gtfaafjyuw.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtryjxuwbl.html

[S03] C：读入整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhoivkho.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtacgcispf.html

[S04] C：字符串复制
来源：http://dali.xuetiantiany.cn/Article/details/gtkdlupilk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gtkffigeln.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gthhobfbjf.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtqjoeizom.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtezczzrok.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtucedcvfh.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gticixkzek.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtagjptwgb.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtcylomsbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gtuwedorob.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtjzfuphlr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtlhmczxzh.html

[S10] C：指针与解引用
来源：http://dali.gaohongyu789.top/Article/details/gtkptytzoc.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gtvfmcwxce.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtxhsslyru.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtyycpnpvc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtupfyupfb.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtzvomnjrq.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthlkxrru.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbocjttxo.html

[S13] C：宏定义
来源：http://dali.sufxvd.cn/Article/details/gtbvbdewxk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtexpxnqql.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtwpamfftl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtcpewqmpj.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gthybcjbyn.html

(double) a / b
来源：http://dali.meibo888.top/Article/details/gttmydkidr.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtmguxvqpw.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtygknlwla.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtfdezcizb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtimqrcfie.html

[S18] C：命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfysmwdr.html

int main(int argc, char **argv)
来源：http://dali.xuanzx.com/Article/details/gtcwxadubx.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gtuukctfhb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtjsgfhdhg.html

[S20] C：二分查找
来源：http://dali.hywenlv.cn/Article/details/gtplyotmwk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtkymjcmdk.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtfyzlvqxc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtukowdqqb.html

[S22] C：字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gttvrpakab.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtpzrkgaii.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtgmkdurwv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtrhuqukfe.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtnobqneqt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gthwarjyrt.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gtzylunayg.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtgdrljykw.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtxjxksdjj.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpokqwjjp.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtwnpuzxol.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gttxqljyaj.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtngswbzwl.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtiuowbhsl.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtedeuvxii.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigfzy.top/Article/details/gthpkhzosw.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtotgqupnm.html

#ifndef X_H
来源：http://dali.xinyue.icu/Article/details/gtgarzdkbc.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvjemecr.html

#endif
来源：http://dali.ivvv.top/Article/details/gtgzgrytfe.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtkpvxbccm.html


<!-- 参考信息 -->