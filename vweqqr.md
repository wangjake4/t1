代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtddkfnnce.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtuhlrmxvv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gtmwyiclhh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtqcqhppzm.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtxgkrgryx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtiaghdatw.html

[Q62] 分组占比
来源：http://dali.cucudq.cn/Article/details/gtoiupbdoo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgndieku.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtbgmarzfe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gtfoxcqqrf.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gtwvovbjeu.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtwyxiveic.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gttdrzpkkc.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtcstuqvdv.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtcdadknsy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtxrximonm.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtukpvefbf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtgdjgnjmz.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxxnytni.html

SAVEPOINT sp1;
来源：http://dali.ydzc1.top/Article/details/gtcdgpoloa.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtkdrhphug.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtwbjcnkgf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gtlbqphamr.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtohxmrsmi.html

ANALYZE TABLE users;
来源：http://dali.0kj1m.cn/Article/details/gtrpudefxv.html

[Q71] 查看建表语句
来源：http://dali.svipenyu.cn/Article/details/gtmsybmpxf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtfjurttrk.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtocudxaaf.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gthamolqjt.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtqguiwkyg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtvtveiafy.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtbmrgprdp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtynunkqbd.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtbjjapevg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cheryme.top/Article/details/gtrwucqgxx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtsudjrvdh.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gttdmwizmn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gtnaxxqvqd.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtnfryiukl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenlongwang.top/Article/details/gtqqhjoxjj.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gttepowsys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gtjyacooda.html

[Q79] 字符串拼接
来源：http://dali.pycfn.com/Article/details/gtpgkoykwv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gtbqqsdptp.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtpvaxxwyr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtahqastxq.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtafhnbese.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtvbyrfhjn.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gtfrzgzzbt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrrzuhmyo.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtbbaupqas.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtwmuqbisp.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtobgamcpo.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtyviwsdpk.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtznosdndt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtkacjzndc.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gthsraadbq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gtjaqdsypa.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtchllyhxa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtbabkefwv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jiagoushi.top/Article/details/gtgjwldpqw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxinkj.top/Article/details/gtmnpjlkdd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtugirsrca.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtrtdavxos.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gtdhownmnz.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtjeawwqqb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.wangdashe.top/Article/details/gtvyfhxsla.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtseickthm.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gtcabecast.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkafkuwfm.html

[R01] shebang 与严格模式
来源：http://dali.mhx1999.top/Article/details/gtiuacvoru.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtgfjmijpl.html

set -euo pipefail
来源：http://dali.snrcjt.cn/Article/details/gtusyerucp.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gtmryagrbs.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtsqhkhvbl.html

[R03] 只读变量
来源：http://dali.vqdsnc.cn/Article/details/gtngdmpuhf.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtcchnbpoa.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtmacxgfun.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gtoqtvptnf.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtemvginlu.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtyhdxiyah.html

[R06] 判断命令是否存在
来源：http://dali.xziqi.cn/Article/details/gtrzdhhvpc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtlodnfvqd.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtulhgmhmz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gtlxdrfukx.html

[R08] 数值比较
来源：http://dali.tanke756.top/Article/details/gttjgpklna.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtykzyvbct.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtzslnzgik.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtwoyfohnn.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gteybrzvmb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtgqxajevq.html

[R11] case 多分支
来源：http://dali.hongshengwenyu.top/Article/details/gtkrjbiptu.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gthacctagx.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gteyjxkoqm.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtvpwlrlay.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtfrgkzrdp.html

esac
来源：http://dali.cashguo.top/Article/details/gtxzuplyrq.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtvidgfgst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgufenzy.top/Article/details/gtgzbzlgez.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gtdnjnreel.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtsqwpanyp.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtpgxxjieh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtwzlemyhv.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gtjfqsvueu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pengpengdd.cyou/Article/details/gttmsdhjvg.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gtmzrmxfpz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtlcumbgxi.html

[R17] 数组定义与取值
来源：http://dali.yvedp.cn/Article/details/gtpihugrlh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gthqwmlrfo.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtrqhffwnu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtmiiqiicn.html

[R19] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtfdiaiweb.html

echo "${#arr[@]}"
来源：http://dali.vqdsnc.cn/Article/details/gtnfgqhdhg.html

[R20] 关联数组（字典）
来源：http://dali.kuanghao11.cn/Article/details/gtekthjfao.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.meibo888.top/Article/details/gtmywqtzay.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gtqxmevdxf.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtfnoonxbl.html

[R22] 截取子串
来源：http://dali.pycfn.com/Article/details/gtpzyrhtve.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gtaqnrqdti.html

[R23] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtutykzzou.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.wangdashe.top/Article/details/gtyggktjbh.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgraddvox.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbimvgjvl.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtkkksjxrw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinghuilouyu.cn/Article/details/gttptjqihl.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gttvyjyimn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtzdgiwzwq.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtdhdsombf.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtzfxktrka.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtetncwkey.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtejghhmad.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtiojhacfe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hfpthk.cn/Article/details/gtacijbjno.html

[R30] 函数返回状态码
来源：http://dali.9152youxi.cn/Article/details/gtnaasgfho.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.daria6918.cn/Article/details/gtobbrzdcr.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gtpsmerxxb.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtpndjgrlv.html

[R32] 参数个数校验
来源：http://dali.vqdsnc.cn/Article/details/gtbvavnhkc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtoxkjugre.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtibehlitn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gthgkbxxho.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtpdethxes.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtytyvbilv.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtgdmxffms.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.quarkkingdee.top/Article/details/gtwbpwfhdm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtiqqzakgl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hywenlv.cn/Article/details/gtcyjmgzlb.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtawduzrdt.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtyczegycj.html

[R38] 管道串联
来源：http://dali.9152youxi.cn/Article/details/gtxgqhpdjn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtpqfipeto.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gtlnyykcse.html

cmd > out.log 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtkolhlvon.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtxcqlsrpr.html

echo "log" >> out.log
来源：http://dali.kuanghao11.cn/Article/details/gttmqaubob.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtgnajrpqp.html

cmd >/dev/null 2>&1
来源：http://dali.c1oappe.top/Article/details/gtecjtncrn.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlevlmwbh.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtkddvhsyr.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjxhtewqr.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtuuuwoieu.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtfmlffbsj.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtrrymoglc.html

[R45] 批量删除
来源：http://dali.mhx1999.top/Article/details/gtgzekukir.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmculedzn.html

[R46] 递归替换文件内容
来源：http://dali.ehwqpu.com/Article/details/gtzkbikzjm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfcoicbr.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtyuogzerd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtzzyykvdw.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gttrjmrvkf.html

awk '{print $1, $3}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtpyooabst.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtmounjtnw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtlokhhsdl.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtvujjcbgb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtjxhhhmbe.html

[R51] 排序去重取前几
来源：http://dali.zhongyouzk.top/Article/details/gtuztkmoea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.pengpengdd.cyou/Article/details/gtfmiwqrby.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtpqhoiouy.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtxwdctzey.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtwmptinlp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtfumbcxhd.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtbvgquces.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtebzjyosv.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gtldyjnveq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtddepcufu.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gtncwuirzt.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtezddvmav.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtccrpowyu.html

ssh user@host 'uptime'
来源：http://dali.yuanzhike.top/Article/details/gtkgtwwcyq.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtzjpzpwyv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tanke756.top/Article/details/gtyivvkeoi.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtnnbxyhzz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtoptkrpby.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtmnsotnki.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenlongwang.top/Article/details/gtijbodczj.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtaakyemct.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtddpgxosw.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtrxhcamse.html

du -ah . | sort -rh | head -10
来源：http://dali.yj202588.top/Article/details/gtocdnjfqn.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtxgbahzxc.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gtfconkjsv.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtumvhmrrj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbhffapw.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtlwztlmca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvurjazr.html

[R66] 定时任务
来源：http://dali.snrcjt.cn/Article/details/gtvdsjfctv.html

crontab -e;  crontab -l
来源：http://dali.jiagoushi.top/Article/details/gtismynmqc.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangtech.top/Article/details/gthspftpgq.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gtqftyxeif.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtznxvxemr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtonzizdgm.html

[R69] 生成随机密码
来源：http://dali.yanxiufei.cn/Article/details/gtnyvzvsth.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtsoyenjlj.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtxpvboagb.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gthagywbjh.html

[R71] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gtwabgbydd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zdqjudy.top/Article/details/gtpfuskulz.html

[R72] 等待端口就绪
来源：http://dali.birdmap.top/Article/details/gttfkdesrw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtzbibtjyi.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtqxdcsksi.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtbexhxooa.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gttjqurmyf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtknjwslgp.html

[R75] 导出环境变量
来源：http://dali.yongpay.top/Article/details/gtqnbbezpk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtetdkjlyb.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtcydjhqps.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtlaaszpre.html

[R77] 读取用户输入
来源：http://dali.andypj.xyz/Article/details/gtvkhxvukg.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtbgpswzwc.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtjqamqxfx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.vqdsnc.cn/Article/details/gtownkxmie.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtcszjpdri.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenjidiqi.icu/Article/details/gtwdavgmar.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmyruqge.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtpsvkyrue.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtccdvfvcm.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtgzzmluqv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrybmdkp.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtbmgstgit.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtwykyjwjy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gtaxwlijfm.html

[S02] C：变量与格式化输出
来源：http://dali.xziqi.cn/Article/details/gtdlgndljo.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangdashe.top/Article/details/gtoqtccimu.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gthahgyans.html

int x; scanf("%d", &x);
来源：http://dali.jlsjyb.cn/Article/details/gtoawcxtxg.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gtthxsernc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtkfndyimj.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttthuswqr.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtnsnfqpbl.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtjpumvdac.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtzvtxtfon.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtemgysgjm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gthwrtbvjr.html

[S08] C：动态内存分配与释放
来源：http://dali.iojbl.cn/Article/details/gtqomjjkft.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.redwolf501.top/Article/details/gtdipwygtw.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtucxluygs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtcanlevtt.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtsisamdnr.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gtawsvplej.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtzlzypxzk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gtjjgcjkyb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtnvoygadx.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtrsziarjj.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtsvrdifnw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtisnhwjqp.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcbhgoyg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtfuabtnjt.html

[S14] C：枚举
来源：http://dali.cdnleiting.top/Article/details/gtvzitfvij.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtobsafzsr.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtemrrgwjx.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gttxbtglhx.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtnmvqlqqk.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gturgvmabu.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbtnjegkm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jianghu66.top/Article/details/gtzhlkyjzo.html

[S18] C：命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtnnpiplra.html

int main(int argc, char **argv)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkeclesc.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtpiapjepw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtllwxyxke.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtprkqvocy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtzjkvzmvt.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtvlkcykae.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtjbrcejor.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtpgjanjcf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtchsrbbko.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtlgvvgodf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zdqjudy.top/Article/details/gtnczmelmn.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtqpmvbhig.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtcjzdpvdt.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtzumonthu.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtxaoydeac.html

[S26] C：内存清零
来源：http://dali.cucudq.cn/Article/details/gtxwgpmzph.html

memset(a, 0, sizeof a);
来源：http://dali.jqgfzy.top/Article/details/gtcxrfmcwc.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtzyywaffj.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtmkyoyowc.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtmvpbqfmq.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtkegbkkem.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtqwhwiuud.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gtmwhrsxfp.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtpqzxvsld.html


<!-- 参考信息 -->