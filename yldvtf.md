代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtorgqpogx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhixingplan.top/Article/details/gtugdgbpjq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtdgitbnbm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gthgaeqhog.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtqbauktvi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtjgleyooj.html

[Q62] 分组占比
来源：http://dali.hysaishi.cn/Article/details/gtefssgskh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtjdlrarem.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gteigyxsrk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtsjgpwrhl.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtbjfqqhmt.html

COMMIT;
来源：http://dali.zhixingplan.top/Article/details/gtueiuatym.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtratabeyf.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbhfnipw.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtraqxkutl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtqnkjrygf.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtionssfez.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.9152youxi.cn/Article/details/gtvuqxthut.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtmetwdaxw.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtktbamfvf.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtesciyfqn.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gtmmlicjwx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtzjvvljrk.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gtlulzajkc.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gthanrlgdv.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gthiujddmp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtzuudfotp.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtdssgzhfz.html

SHOW INDEX FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtiewekota.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtpbhskiqa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdcifark.html

[Q74] 强制使用索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxcfwzzf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtfteznkwe.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtagmnodqx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtiydbxfac.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtdkeutixy.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtuotwqhkv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtfxlokmkq.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gthtkzuvgm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ppjwa.cn/Article/details/gthmrjbvbl.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gteonomqfn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtxelqjtnk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtxbjtdabk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhoulong.xyz/Article/details/gtzzfoqdvl.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtmwhrsiyr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtjqvxbrgd.html

[Q81] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtwasttmmt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtanzhtang.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtqbmlmaoo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxffjcyw.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtakpxzkoe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtjqzjuhwj.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gtdxtmybhp.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtqqsvxniz.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtctloxuey.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhiwuduotai.top/Article/details/gtetvaxomp.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtgphouwph.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.quarkkingdee.top/Article/details/gtznrqnucg.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtsrzukyld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtuvzktinq.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdednehtp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.pengpengdd.cyou/Article/details/gtfujjutoh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtinqnkjei.html

[Q89] 判断表是否存在
来源：http://dali.iojbl.cn/Article/details/gtgdfprmmv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hywenlv.cn/Article/details/gthakfjamz.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtkuqvqdgu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtnfmanuab.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlymncvpd.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtunalbjjp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtijaxwzev.html

[R01] shebang 与严格模式
来源：http://dali.ybcxt.top/Article/details/gtsciijpmy.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtwdxiqlrs.html

set -euo pipefail
来源：http://dali.shuidangran.top/Article/details/gtkmgertcd.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gtwsevypww.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtrhqsxlcj.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtruyqmucw.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gtqndkzcoo.html

[R04] 位置参数
来源：http://dali.hfpthk.cn/Article/details/gtsucnctdr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gthrnqnwrz.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtnioiriyw.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtzuuoizww.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtuvopanrv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtddsmtafm.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gtenhndcnc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtglknszof.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gtehwuvept.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtsrkunhmq.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtgaajsmbk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtqkvyufnt.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gtsqujjmqi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhengqikj.top/Article/details/gtsnkokoxh.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gtvqsbwsrq.html

case "$1" in
来源：http://dali.hammf.cn/Article/details/gtdbblpuvk.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gtudvtyfti.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtjezbesjq.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtyigihwhz.html

esac
来源：http://dali.ivvv.top/Article/details/gtygdftxqe.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gtajtdylsg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gtntchxsan.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtxuvutfgo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtcdyfkmmo.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtwdyguxfc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtvmtockos.html

[R15] while 逐行读文件
来源：http://dali.ivvv.top/Article/details/gtcdwdyxoe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ehwqpu.com/Article/details/gtgwbdxugo.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtasukpwzu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtvybrcpor.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gturzqlksx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gtfwpanyuv.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gtumsrvind.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtgfxyocbw.html

[R19] 数组长度
来源：http://dali.bjfxy.top/Article/details/gthdqxghfv.html

echo "${#arr[@]}"
来源：http://dali.xuetiantiany.cn/Article/details/gtupnodigp.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gtbojbcrvm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yonumen.top/Article/details/gtkwagwrcc.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtyozjhbtk.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzbkwhuo.html

[R22] 截取子串
来源：http://dali.jinqigfzy.top/Article/details/gtdfjrpjxh.html

echo "${s:0:5}"
来源：http://dali.aibaodan.cn/Article/details/gtjeodkakj.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtbhwgqfcu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.feifeiyinyue.top/Article/details/gtbqlkgwny.html

[R24] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtmrrkunsi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtaghgvgcx.html

[R25] 去后缀 / 去前缀
来源：http://dali.dianchejie.cn/Article/details/gtcztrndsz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtiddymmke.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtmuifzaey.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gtlfkbxxlj.html

[R27] 算术展开
来源：http://dali.fengsongda.top/Article/details/gtrywqeezv.html

echo $((1 + 2 * 3))
来源：http://dali.aibaodan.cn/Article/details/gtakhglnen.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gtrohrgsgk.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtixvkjnmc.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtzephatqb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gtrptggxrb.html

[R30] 函数返回状态码
来源：http://dali.jiagoushi.top/Article/details/gtysmjwgko.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gtjtkhifjo.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsedjjcqh.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtmwlosggf.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gthajponyq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gttkhtodal.html

[R33] 捕获错误并提示行号
来源：http://dali.jyoumei.cn/Article/details/gtmvetyfmx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtsjsxljsk.html

[R34] 退出时清理
来源：http://dali.jyoumei.cn/Article/details/gtanabhvwq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtkyophpsw.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtifvpuzst.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gtqvttdlpd.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtgeyigtdo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtpooamxhy.html

[R37] 把输出赋给变量
来源：http://dali.jiagoushi.top/Article/details/gtbeakwtwy.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtgnawcoms.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gttupnqypa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.birdmap.top/Article/details/gttqkvrnpd.html

[R39] 重定向标准输出与错误
来源：http://dali.xuanzx.com/Article/details/gtnwvvfojx.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmbehxpt.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtgektiwix.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gtskunettw.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtxptdnxzl.html

cmd >/dev/null 2>&1
来源：http://dali.hammf.cn/Article/details/gtdtzlkbii.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtghgksmwj.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gtvqjtnusi.html

[R43] 按名字查找文件
来源：http://dali.yj20258.top/Article/details/gtqppajqws.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtcosoqshi.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeygrkpd.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtxskgksjn.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gtelqvlrul.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtnnfqxzkk.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsynqvqc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gttyatxgdp.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtebmbeidl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaedacuj.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gtcngkmenm.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtggtzscow.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtqrjljflp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtgrqilehs.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtcqcwitxp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtvsusuudl.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtwpinzfgt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daxiang520.top/Article/details/gtigcdmojd.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtjsyctebg.html

wc -l a.txt
来源：http://dali.yonumen.top/Article/details/gtsjpxdnov.html

[R53] 查看文件头与实时尾
来源：http://dali.zhengqikj.top/Article/details/gtrhbwytio.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtorughycu.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtfkretl.html

diff a.txt b.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtfbscraiw.html

[R55] 压缩与解压
来源：http://dali.jlsjyb.cn/Article/details/gtmfgvkmxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gtdmrinpvl.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtlrusgrfn.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtigvpjsbe.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtrctfhggq.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtccbawydz.html

[R58] 下载文件
来源：http://dali.cqqwz.cn/Article/details/gtpchyrfvx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtezrzltqv.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtqtcfnwye.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtfpktesga.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtwdpphjql.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtekakzzfa.html

[R61] 磁盘占用
来源：http://dali.0kj1m.cn/Article/details/gteuckztgl.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtahgcnxfl.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtktuzsfks.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtnkxjsstg.html

[R63] 内存与进程
来源：http://dali.cdnleiting.top/Article/details/gtjkmkcwfw.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gtvejtvyvp.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtzlozwisg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtaidpfqhf.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtcvbjqnkn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtsrfclfso.html

[R66] 定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtdmypuzut.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtoyvqodbl.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtsailysdy.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gttfxupkri.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtlwoangsr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtwsoatvij.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gtzmlzxnmb.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtibcmxvvf.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtxzgbkygs.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtyjipofvg.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtwenbkeur.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtnpusxswa.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcczizroy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtkaqxenrp.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtvfhhgwqd.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtardzccym.html

[R74] 批量重命名
来源：http://dali.vqdsnc.cn/Article/details/gtkzxpvtwz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtypetvwpi.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtxqczngxl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtumhvhvgb.html

[R76] 使用临时文件
来源：http://dali.jqgufenzy.top/Article/details/gtslqjfpxr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotyskgrd.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gtrjyaivhv.html

read -rp "请输入: " ans
来源：http://dali.hywenlv.cn/Article/details/gtzeomjwdu.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtmryujzbe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtmcxxydhc.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtzggscbtq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtvkzxblwc.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gteoiybnbk.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrorjakcq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaerkieg.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtjuizjvfz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmhtoqrcr.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtitlujors.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtocmohtgv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuetiantiany.cn/Article/details/gtupyeuhao.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtnkoshvsy.html

int a = 10; printf("%d\n", a);
来源：http://dali.cucudq.cn/Article/details/gtrlqmrwvi.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuahpmnzz.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtlmwbolli.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtbykuqlml.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtqqgyqbqr.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtngvhamrp.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtcujtgbwt.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtubdmgozg.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtevkmiqpl.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtwwbiolky.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtteroftaq.html

[S08] C：动态内存分配与释放
来源：http://dali.yj20258888.top/Article/details/gttnxyvkyw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuetiantiany.cn/Article/details/gtmgmbygpy.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtnnemeidy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtdvmddbrk.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtyazqtvje.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfalsmkm.html

[S11] C：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtsojurlka.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtwutgomhu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.aizwys.cn/Article/details/gtbwhvnurv.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtanqrrnwa.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gthjrgbhvl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtdfgizvoy.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtdezldbim.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnqzz.top/Article/details/gtudnnrowm.html

[S14] C：枚举
来源：http://dali.andypj.xyz/Article/details/gtdwlshqvu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtcirmeexr.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtialatxya.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtjulhsooj.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtddecgcgg.html

x |= (1 << 3);
来源：http://dali.zhoulong.xyz/Article/details/gtkdkihwmh.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtbfxaqphs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj202588.top/Article/details/gtlasbpuhh.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhatktkp.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtozlmvqjv.html

[S19] C：快速排序
来源：http://dali.zhengqikj.top/Article/details/gtvzguyqlx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtqtbgfheg.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtgxyooiaj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtczcfcfgq.html

[S21] C：字符类别判断
来源：http://dali.vqdsnc.cn/Article/details/gtrzkjfenc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtsxnwykmk.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtanxwvgok.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtvkgnhjjt.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gttdpncuzt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.andypj.xyz/Article/details/gtkpnzspwr.html

[S24] C：获取本地时间
来源：http://dali.0kj1m.cn/Article/details/gtivcyegly.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xinyue.icu/Article/details/gtppqnsrpf.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtfwrymlgz.html

memcpy(dst, src, n);
来源：http://dali.xinyue.icu/Article/details/gtbvotqrna.html

[S26] C：内存清零
来源：http://dali.zdqjudy.top/Article/details/gtksbwklmx.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gttqiojdsr.html

[S27] C：定义常量
来源：http://dali.chenjidiqi.icu/Article/details/gtrrngbmpc.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtynsnolvw.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtvhmuqras.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkviubwcs.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gtfftxogep.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtpdvajkuk.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtcyuoivxu.html


<!-- 参考信息 -->