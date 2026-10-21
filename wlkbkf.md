代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gtxnfqexal.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtogjrzkoh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gtiqcllxgc.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gtfjswfkoj.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtdqsqjgqi.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gttudzwqfb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtbrolgtom.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtgthhhbwf.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlieedrll.html

[Q73] 查看表状态
来源：http://dali.birdmap.top/Article/details/gtnffwsgjm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtlznpxson.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtoyccblmj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtqrjdifgc.html

[Q75] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gthmimhaki.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtneyzmhgy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxinkj.top/Article/details/gtuhcbsrgt.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gtzyvmucjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gtagaiseto.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtpjnufwuc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yangfankeji.com/Article/details/gtsgimqkqj.html

[Q78] 当前时间
来源：http://dali.iojbl.cn/Article/details/gtrxbczkxy.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gtdtrphegb.html

[Q79] 字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gttrobuwxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtgrivrske.html

[Q80] 字符串截取
来源：http://dali.vqdsnc.cn/Article/details/gtiikxtixg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gthccenixm.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtxzxspigq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtonoojszi.html

[Q82] 字符长度与字节长度
来源：http://dali.aizwys.cn/Article/details/gtnkuasvab.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtvxgmqujk.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gthrybveoe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtlnnlogjv.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtrcshydbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtejxjudph.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtordhqsyd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gttnnekesc.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtbliloniw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gtggcccxmv.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gteysgsmrz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtsaqlyesx.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaripwvo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtshtyewdu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtwcwgzpah.html

[Q89] 判断表是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtgmcfjqap.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtolcyuyaf.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gttbudrwba.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtsvztggru.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwgotujze.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gtkdzjkvkv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtmaetasbx.html

[R01] shebang 与严格模式
来源：http://dali.xuanzx.com/Article/details/gtquhvuqwg.html

#!/usr/bin/env bash
来源：http://dali.iojbl.cn/Article/details/gtzbcpjyaz.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtpkrsffgi.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtenmeewkj.html

name="Tom"; echo "$name"
来源：http://dali.snrcjt.cn/Article/details/gtkzsdgemf.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtiwzcmspm.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtwszgtuwd.html

[R04] 位置参数
来源：http://dali.hnqzz.top/Article/details/gtcalyzqwe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtwgccdcaf.html

[R05] 参数默认值
来源：http://dali.yongpay.top/Article/details/gtgbdexefn.html

name="${1:-default}"
来源：http://dali.daria6918.cn/Article/details/gthbehfbbi.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtchpbshco.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtvutdfplq.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaydqwrg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpwbidng.html

[R08] 数值比较
来源：http://dali.zhixingplan.top/Article/details/gtcfpldgsx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtmiwmiehw.html

[R09] 字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtiuihadve.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtebuussco.html

[R10] 正则匹配
来源：http://dali.kuanghao11.cn/Article/details/gtxnutjxuj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtmqsktldp.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtyuvklgpf.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtlsegljsi.html

start) echo "启动" ;;
来源：http://dali.gotoacloud.top/Article/details/gtjfhlrvnb.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflwsoloq.html

*)     echo "未知命令" ;;
来源：http://dali.hywenlv.cn/Article/details/gtrkwixwvk.html

esac
来源：http://dali.zhengqikj.top/Article/details/gtfswetnyv.html

[R12] for 遍历文件
来源：http://dali.jianghu66.top/Article/details/gtczpoioia.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gtbswfhfcn.html

[R13] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gthvpklvwf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gtusoiganr.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtihdkfslw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtupibarrj.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtstyekdqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.gaohongyu789.top/Article/details/gtixkjwdso.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtyxdljxyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtuvcapuif.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtyairktfg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gtvmkxtuub.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtzgydeujd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtacdjrznb.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtpvbcaxtb.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtsuimqzhw.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gthmjpfxlk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtsuwupeet.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtbgxttsrg.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gthtyslztz.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gtseofshyh.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gtpadarndn.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtcyulgzkn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhongyouzk.top/Article/details/gtqwfhiuwk.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygepwrbv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gotoacloud.top/Article/details/gtkwgdmqaq.html

[R25] 去后缀 / 去前缀
来源：http://dali.birdmap.top/Article/details/gtyewpeibr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtnskxruwu.html

[R26] 命令替换
来源：http://dali.jiagoushi.top/Article/details/gtkjkzazbt.html

now=$(date +%F); echo "$now"
来源：http://dali.shuidangran.top/Article/details/gtgcrktmin.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtelgvfygy.html

echo $((1 + 2 * 3))
来源：http://dali.tian-w.cn/Article/details/gtozshzwnv.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtfkkcwncg.html

echo "scale=2; 10/3" | bc
来源：http://dali.shzxlz.cn/Article/details/gtkohnssjg.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtzvhwhrdz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gtwrcaclqf.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gteolqxuod.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gthwbsnkra.html

[R31] 局部变量
来源：http://dali.meibo888.top/Article/details/gtawtdhzfn.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuanzx.com/Article/details/gthiiwxjsi.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtsztepndb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gthwooitqu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtiosgfssf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.9152youxi.cn/Article/details/gtftizlghr.html

[R34] 退出时清理
来源：http://dali.svipenyu.cn/Article/details/gtxutolkfl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtllgfjyuz.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gtcwmuqxqy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtoujqpdbm.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtnmescckh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtpsqfsvjs.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyehhvez.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtgstuvdsq.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtedgygpbk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhoulong.xyz/Article/details/gtsmqbulav.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtnjrbintl.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtydomhqzp.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtkcgrrrln.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gteuwnkdkz.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gthebgqhgo.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtznwcxpyl.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gttvzkpwau.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gtuljlrswo.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtroqtqbju.html

find . -name "*.log" -type f
来源：http://dali.sxryk.cn/Article/details/gtwnewgfvj.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gtvhbchvlo.html

find . -mtime -7 -type f
来源：http://dali.quarkkingdee.top/Article/details/gtcmfoflwy.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtfcwffypn.html

find . -name "*.tmp" -delete
来源：http://dali.ydzc1.top/Article/details/gtibkcrsfe.html

[R46] 递归替换文件内容
来源：http://dali.jyoumei.cn/Article/details/gtkqrslkgo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtnorstfli.html

[R47] sed 单行替换
来源：http://dali.ydzc1.top/Article/details/gtznqyxkcq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sweek.top/Article/details/gtjjekjcck.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gttcjcdmbh.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtsabiygll.html

[R49] awk 带条件
来源：http://dali.jinqigufen.top/Article/details/gtryrzwcea.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtmfpobmxt.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtyuyvcgsw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtuhbsqwkq.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtvbeeybpe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gtgtdqkodb.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtolhnaxnv.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtbkeqxxdi.html

[R53] 查看文件头与实时尾
来源：http://dali.jyoumei.cn/Article/details/gtdtazhcwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtcnohassw.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtmiykotjs.html

diff a.txt b.txt
来源：http://dali.yuanzhike.top/Article/details/gthhpapkob.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtasezzmae.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtxupkzquc.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gtynnzizbw.html

scp file user@host:/path/
来源：http://dali.mhx1999.top/Article/details/gtshehnviz.html

[R57] 远程执行命令
来源：http://dali.daxiang520.top/Article/details/gtefnvhgpy.html

ssh user@host 'uptime'
来源：http://dali.yonumen.top/Article/details/gtebzdgcfy.html

[R58] 下载文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyhtqido.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangdashe.top/Article/details/gtlhpaqvvb.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtnkeywkmb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtybobnypf.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gttnhiaoko.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtgnhsnhqo.html

[R61] 磁盘占用
来源：http://dali.yanxiufei.cn/Article/details/gtzfmyvytd.html

df -h;  du -sh *
来源：http://dali.0kj1m.cn/Article/details/gtdexjfnon.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gthbtxahur.html

du -ah . | sort -rh | head -10
来源：http://dali.gzhubu.top/Article/details/gtogpthpwu.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtpbkauafb.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtlheochsz.html

[R64] 结束进程
来源：http://dali.xuanzx.com/Article/details/gtheqgxbej.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtbyaorysa.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtdlmbeomd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtumhcieli.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqcehdktz.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtdgastdjp.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtlatuudhx.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtuwxftqwe.html

[R68] 计算文件校验值
来源：http://dali.mhx1999.top/Article/details/gtlbzyzbbw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmplnmbko.html

[R69] 生成随机密码
来源：http://dali.tanke756.top/Article/details/gtraavfkob.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtqosneufb.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gtxtlfyyoe.html

date +%s;  date -d @1700000000
来源：http://dali.shangyingyoupin.top/Article/details/gtfynhdwef.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtcfbaaunx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtumeldgur.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtryjoanpy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gthupmmevd.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtcrmhzeyc.html

split -l 1000 big.log part_
来源：http://dali.birdmap.top/Article/details/gtpziveaxs.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiwpilid.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtotvcwimx.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtsqsqqwbl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtlfnvgmbu.html

[R76] 使用临时文件
来源：http://dali.sweek.top/Article/details/gtwtcetwvb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtwkxxzjik.html

[R77] 读取用户输入
来源：http://dali.jqgfzy.top/Article/details/gtqdykvgxe.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtqypswpdf.html

[R78] 交互式菜单
来源：http://dali.fzhhl.top/Article/details/gtqgvufhwy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gtymocqxyl.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtrbfqvgvj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gtpgkfsvfc.html

[R80] 查看脚本执行耗时
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtfemfpi.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtivxrwczf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgwjziqna.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtritdmsyg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbemngxkw.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtepdwzauy.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtaaeuxfci.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gtcflafcmq.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtthamhsbb.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtagicotga.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtvndykvqi.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gtygbnbytn.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtgorogmoz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtexlecgyy.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtpbsnqikj.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtxxybbvnq.html

[S06] C：字符串比较
来源：http://dali.yj20258.top/Article/details/gtdleqbzpk.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtnrqyqxeq.html

[S07] C：数组遍历求和
来源：http://dali.tian-w.cn/Article/details/gtpcsgmrss.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hammf.cn/Article/details/gtbckdnhow.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtrnqmjaku.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xinyue.icu/Article/details/gtthfzgexn.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtwlaszyxn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cucudq.cn/Article/details/gtjjvnutwf.html

[S10] C：指针与解引用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzcqjyct.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrewwumq.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtufixriun.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtrpkuzsvh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ivvv.top/Article/details/gtmtqpamru.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gthtzfqxim.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtpprshpty.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtqffujbkt.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtxokalcst.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtuimquzui.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtfoecacjp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.kuanghao11.cn/Article/details/gthuutyeiz.html

[S15] C：类型转换
来源：http://dali.dashuyun.cn/Article/details/gtbnfpsexo.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gtmcvhiumg.html

[S16] C：位操作置位
来源：http://dali.xuanzx.com/Article/details/gtuxzvycqk.html

x |= (1 << 3);
来源：http://dali.ivvv.top/Article/details/gtwwnjgzvf.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtqhqrqxul.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtozuyosrr.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtjkzrdpdq.html

int main(int argc, char **argv)
来源：http://dali.feifeiyinyue.top/Article/details/gtzakdfuee.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gtqbrbnkms.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtvkuqivlr.html

[S20] C：二分查找
来源：http://dali.cdnleiting.top/Article/details/gtszjcchfr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtcapusqbe.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gtdildnkgg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.birdmap.top/Article/details/gtlcxrvtfx.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtsgxonxbk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtevzcbgnl.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtxcnuqaul.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gtkprzvmhq.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gtqjaqfgxw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtyjsvsxiz.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtzpmkpyrq.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtzambmubf.html

[S26] C：内存清零
来源：http://dali.shzxlz.cn/Article/details/gtllfaxopu.html

memset(a, 0, sizeof a);
来源：http://dali.aibaodan.cn/Article/details/gtlqifvjjk.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtmrtolbwg.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtxolsezne.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtzkofhztw.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtzbtfhdaa.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtdejvkkon.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gtodyjmvcs.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gttwhjsmxx.html

#ifndef X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtuedyuuwp.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtpqkusswd.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtfrhnxgjl.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtiynjhbhm.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtdqqbqdpb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtijzlggtk.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtktombpwi.html

std::string s = "hi";  s += "!";
来源：http://dali.316326.xyz/Article/details/gtgkhvygvl.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtxziqppep.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shzxlz.cn/Article/details/gtyjzolfei.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gtmvnxolmv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtfotrwapa.html

[S35] C++：map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzohqvjlj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtndwygoiv.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtgviowxmz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtdyrxxznv.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtttouormk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gtqvdksety.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gtassxdpkz.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gtzsznncga.html


<!-- 参考信息 -->