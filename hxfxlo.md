代发 wailian999

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtpxctwuuc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gthrmuinqn.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtwxgjlpel.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtetyjpcny.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtgwvxbgji.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtqebsfhml.html

[Q66] 行锁查询
来源：http://dali.jinqigfzy.top/Article/details/gtyqemevgv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gtpflhbegd.html

[Q67] 设置隔离级别
来源：http://dali.hnqzz.top/Article/details/gtontrsptv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtrjknfgac.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtjzvbjqse.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtwwnxqndh.html

ROLLBACK TO sp1;
来源：http://dali.sufxvd.cn/Article/details/gtjwvgmkvq.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtbdorqhvz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gtjrszhhfg.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gtrgefeabw.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtddoklrtb.html

[Q71] 查看建表语句
来源：http://dali.jlsjyb.cn/Article/details/gtzqqvqjhc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtvdqwfmyv.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gtdamqqzui.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzlyaxyu.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtuapkcjxa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gtuzlqztlx.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtmkxevgkl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtcahszvqg.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtjywpvlsi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtrekaerdx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtetcvclwe.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gtioxzkmuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmzlgmvz.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtmxhwetjk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtxprucbxf.html

[Q78] 当前时间
来源：http://dali.haohaochexian.top/Article/details/gtijcejhtl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtbirnwujd.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpvomgglo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigufen.top/Article/details/gteeyownsj.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtptmaqfia.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtujixykaf.html

[Q81] 字符串替换
来源：http://dali.snrcjt.cn/Article/details/gthblrbwhd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtbosceuql.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gtnsrxglej.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjigotars.html

[Q83] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gtphthqoak.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsbymveua.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtihjtobpx.html

SELECT TRIM(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtueyhqzxx.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtxitcumhh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtermwfwil.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gtmnpefrzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xylfe.cn/Article/details/gtjdzdyimk.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiobbkku.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtnwqeigdm.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtvaqtztdc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtknqnpuxa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbbzqbmrs.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtilnwyfwh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gtmgfzicha.html

[Q90] 生成序号列
来源：http://dali.chenzaomai.com/Article/details/gtfddmkhjt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtwjycmopc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjlkrdcud.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtwiongrqx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtybjlahgf.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtxhwhslnl.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtwkrjfnkb.html

set -euo pipefail
来源：http://dali.tianlin.xyz/Article/details/gtxcyoxfby.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gtiosauyzi.html

name="Tom"; echo "$name"
来源：http://dali.yuanzhike.top/Article/details/gteosipiin.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtpdbeehdg.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtfvqfeaoe.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtygnfmlgy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zycfv.cn/Article/details/gtoetsxzus.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtrglpuxjh.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtaobxduoi.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtsalrvnof.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gtxpxmgynz.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gtiditqpdz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.andypj.xyz/Article/details/gtddxfcrak.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtiojfmjex.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtrawkgvxn.html

[R09] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtitixzrhg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhixingplan.top/Article/details/gttbnuiyzk.html

[R10] 正则匹配
来源：http://dali.cqqwz.cn/Article/details/gtgruulmlg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gtfjcufssf.html

[R11] case 多分支
来源：http://dali.tian-w.cn/Article/details/gtcyqyxaed.html

case "$1" in
来源：http://dali.pycfn.com/Article/details/gtdblmuvdv.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtorrwkyrl.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtqdvwcpse.html

*)     echo "未知命令" ;;
来源：http://dali.shzxlz.cn/Article/details/gtazkxflsx.html

esac
来源：http://dali.yj20258.top/Article/details/gtdskajars.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtcyarkhlr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yvedp.cn/Article/details/gtbgzztble.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtueagvcxd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yueranfly.top/Article/details/gtjcrypfrc.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gtoeabgokp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtjdghumgw.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtkdncipfv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gtoazdwabp.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gtjonwznek.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtesueoehe.html

[R17] 数组定义与取值
来源：http://dali.meibo888.top/Article/details/gtrgbdsdxn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gtlrtcitxx.html

[R18] 遍历数组
来源：http://dali.zycfv.cn/Article/details/gtxssbisft.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtyxqkspii.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtbdiiaqqt.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtskrlaife.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgxjafth.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gtcnfwkcjl.html

[R21] 字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtpamvjfxc.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtxpfjrfcr.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtapwwahzl.html

echo "${s:0:5}"
来源：http://dali.sweek.top/Article/details/gtctbxnxvp.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtholqqinr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtdpjwkkwy.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gthrfcnhlr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gzhubu.top/Article/details/gttuqsyurc.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gtxxrrcext.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtmbumomji.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gtahvybcfo.html

now=$(date +%F); echo "$now"
来源：http://dali.c1oappe.top/Article/details/gtwghewasa.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmnbtmpg.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtmygeuqey.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnvfcddt.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhongyouzk.top/Article/details/gtaqxrdfmi.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtpkunylzb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtilfixilp.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gtdhclsrtx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtpoorrxkw.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtiemogfxe.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtoevtmdcs.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtijhsgmsf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtfumxbbtm.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtxqleluwa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gthszavhqm.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtumphhbcd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtmnlydylv.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtytolmpnn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtpdxckihl.html

[R36] 并发执行多个任务
来源：http://dali.hnxiangtu.top/Article/details/gttpeghqpa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtfwdkolsl.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtqlewurjh.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gttmqssjrv.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gtydqsevxl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilztzlpm.html

[R39] 重定向标准输出与错误
来源：http://dali.jlsjyb.cn/Article/details/gtoaaurtnj.html

cmd > out.log 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtgnoqvrzn.html

[R40] 追加写日志
来源：http://dali.0kj1m.cn/Article/details/gtwlqlvjqh.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gtvoxxpumy.html

[R41] 丢弃输出
来源：http://dali.dianchejie.cn/Article/details/gtmrooqtzk.html

cmd >/dev/null 2>&1
来源：http://dali.meibo888.top/Article/details/gteswazpve.html

[R42] 输入重定向
来源：http://dali.birdmap.top/Article/details/gtfolamzea.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtxqlkkrsp.html

[R43] 按名字查找文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqfbryngc.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtwrvcvabw.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtvhjnwsfi.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtezdaxebs.html

[R45] 批量删除
来源：http://dali.yueranfly.top/Article/details/gtwahgyhek.html

find . -name "*.tmp" -delete
来源：http://dali.vqdsnc.cn/Article/details/gtzxjdbehw.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtxakbnbli.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtokwnxqnb.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcvmumbl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtclrycdez.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gtpsiqejoj.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtfeghvqex.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtnsinjkzx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gtvzoysacu.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtcjldywcf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtegjruwiw.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtqywbzsbh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gtcjruswde.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gtvmgxiucd.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtklgxqpps.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gtwytflgkz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.0kj1m.cn/Article/details/gtsrdbaoww.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfqwdfcr.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gtjufklvsx.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtxyfzvleo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtwuzvettb.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtjghkycrn.html

scp file user@host:/path/
来源：http://dali.ybcxt.top/Article/details/gtymsjnnbt.html

[R57] 远程执行命令
来源：http://dali.pycfn.com/Article/details/gtszvhcgte.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gtgthpoegr.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtqcnsmwky.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtnggmmnae.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtabwdqems.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdierryc.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gtswijwnhq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yanxiufei.cn/Article/details/gtsgtuluok.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueesvkvr.html

df -h;  du -sh *
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmlfabub.html

[R62] 找最占空间的文件
来源：http://dali.gzhubu.top/Article/details/gtvbcmfauv.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtdsedtxgf.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gtjgtbmxdd.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtavoxdmsm.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtabejoeex.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yueranfly.top/Article/details/gtwacaqqpp.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtbrlirzzk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtqouylecl.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gttluxgfou.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtwtbjihes.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtdaupbrky.html

openssl rand -hex 16
来源：http://dali.cqqwz.cn/Article/details/gtvwaydyof.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtyshgqazd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtwvmfdqtp.html

[R69] 生成随机密码
来源：http://dali.cdnleiting.top/Article/details/gtzpihfcgr.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtejguzofd.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtcvgvrjiv.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtqenkoeeb.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtqihnpyhl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktvvzmnz.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtotldliog.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gttkghwoda.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtpvlbuymm.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtcskzukew.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gtxvlprblh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtwegtnztv.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttxtaldaz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigufen.top/Article/details/gttirfxwdp.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhmyrfao.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtrrouokbe.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtveunjmud.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtjlnuxnfk.html

[R78] 交互式菜单
来源：http://dali.yuanzhike.top/Article/details/gtobrhkqgd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tian-w.cn/Article/details/gtgylzqmjl.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpoeigfw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtlgarizhl.html

[R80] 查看脚本执行耗时
来源：http://dali.yuanzhike.top/Article/details/gtzxtabwlq.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gtdzyfchey.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtldulmqrm.html

S. C / C++ 专题
来源：http://dali.hysaishi.cn/Article/details/gtnmnzthcl.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtckrykddj.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gthvogtlhc.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gtebcbmyyx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtdwzgdjev.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtrdolzhbw.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuktmobh.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtjoitgclf.html

int x; scanf("%d", &x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvneemvmv.html

[S04] C：字符串复制
来源：http://dali.xinyue.icu/Article/details/gtdooxrmqe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtesjznpqt.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtdlscbehi.html

strlen(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzjuyoddm.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtuzzhcajj.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gtpmjukwkg.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtwedcrwyr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtnzowbfeg.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtueufqnmq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtxxlftorl.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaazuynfx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtcapvxljy.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtkghelffl.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtfoyetbyq.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtcpnlqlbg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj20258888.top/Article/details/gtbpoqnhzi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sweek.top/Article/details/gtzlafyoao.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtkhwfjojn.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtypkhusgd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtebpkxypc.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gthaicapxp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtoasmppto.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtekghbxgr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gtuwxpmpmy.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtgbksqbyu.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtriswvfpp.html

[S16] C：位操作置位
来源：http://dali.pengpengdd.cyou/Article/details/gttplfylem.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gtgpmzwmkm.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtbrwocxyq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtlytzaduo.html

[S18] C：命令行参数
来源：http://dali.guannengcc.top/Article/details/gtmqcmzvbu.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtynkayofx.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gthskmbrjj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtszafjbkj.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtbibcngck.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtchvezkoj.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtpanfjrkl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.haohaochexian.top/Article/details/gtiquktyfh.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepsatfqd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtrdhihuqw.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtcqcpthxr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gtdaenzrlv.html

[S24] C：获取本地时间
来源：http://dali.yonumen.top/Article/details/gtduhxhoty.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daria6918.cn/Article/details/gtrmszlvow.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtmtixavgg.html

memcpy(dst, src, n);
来源：http://dali.svipenyu.cn/Article/details/gtklyydnct.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtcgkxinhx.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtnhnhsgam.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gtimpfekqi.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtebepuzdn.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gthcrlnhkz.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtamvbzhpc.html

[S29] C：变参函数
来源：http://dali.zhoulong.xyz/Article/details/gthhqftxri.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtmzrstqxc.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gttllozzpk.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtpuhrpydc.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtvvosmezk.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtxjqcuhfi.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtbmypgvfc.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtjnozappg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtxangzgah.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtwxcijtia.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtnrufocgf.html


<!-- 参考信息 -->