代发 wailian999

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtdtiuwsld.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtiguwdbvs.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtazzstqed.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gtimjxzjnv.html

[Q78] 当前时间
来源：http://dali.fengsongda.top/Article/details/gtndbdfbwf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhoulong.xyz/Article/details/gtyyqryjbo.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtocsvsbzi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtsarfpjty.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gtriiwuirx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtgrmxeajq.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gthgclnvon.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjhhbaqsx.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtjrzdlowr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gteouagesj.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtsdmxonqp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthrmpmuls.html

[Q84] 去除首尾空格
来源：http://dali.9152youxi.cn/Article/details/gtkcsaraik.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtefiuttko.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gtllafrngu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gtxhhnzsou.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtkabfrpbg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtonbfksmd.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuanzsrtr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtoxssllvf.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtptvmovgm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsyamakp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtwvhmaylv.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtuwbphhiw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwpuiqif.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtaeluznwa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtnohmcovn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaupbccqj.html

R. Bash 专题
来源：http://dali.c1oappe.top/Article/details/gttzmtlwhy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtavqihmik.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtfcrrirwr.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gtwruppsju.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtpyfclpyl.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gttjjduyyf.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtkdoicpgz.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtwlhkwfms.html

readonly PI=3.14
来源：http://dali.jinqigfzy.top/Article/details/gtgimjvoet.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfkppcwo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gtirhtoasz.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtesydhcyw.html

name="${1:-default}"
来源：http://dali.tanke756.top/Article/details/gtakrrvjql.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtplybqejp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtdrvzjhdq.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtsoyowdwy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtjyqnlvng.html

[R08] 数值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtjdyttugv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdglbjqkd.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtgsaxawmz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtbfchsrdp.html

[R10] 正则匹配
来源：http://dali.gaohongyu789.top/Article/details/gtcylslugz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yvedp.cn/Article/details/gtfgekloul.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gttxlowznq.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtltwounab.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtdsihbxfv.html

stop)  echo "停止" ;;
来源：http://dali.pycfn.com/Article/details/gtoolcylhq.html

*)     echo "未知命令" ;;
来源：http://dali.xinyue.icu/Article/details/gtvyjoyzph.html

esac
来源：http://dali.havefunace.top/Article/details/gttmgehyup.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gtszcnsvbf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sxryk.cn/Article/details/gtkczpkkop.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtnkysvkfr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gthpznmcbw.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtqfhjvhck.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtxmmkiaum.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtsmygekfk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gtvfpnqygi.html

[R16] until 等待条件
来源：http://dali.chenlongwang.top/Article/details/gteezmetjn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtpmclwnmo.html

[R17] 数组定义与取值
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgkyxsax.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtsceotiwq.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gthgpeumox.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtcjmnmqnb.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gthrknvemq.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtvzurdgsf.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gtrpybukbz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xziqi.cn/Article/details/gtgkddmsjy.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gtdqrjbxvp.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gtbrpluwpz.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtftffutou.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtmiiyllnn.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtxoxmkumy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlfjlcwl.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtheltqjgk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pengpengdd.cyou/Article/details/gtwqfwivzm.html

[R25] 去后缀 / 去前缀
来源：http://dali.tianlin.xyz/Article/details/gthbbzzbvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gtdxmtzmoz.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtfufyshyx.html

now=$(date +%F); echo "$now"
来源：http://dali.chenlongwang.top/Article/details/gtiddpbiza.html

[R27] 算术展开
来源：http://dali.zycfv.cn/Article/details/gtiwteoeog.html

echo $((1 + 2 * 3))
来源：http://dali.vqdsnc.cn/Article/details/gtrjgupcds.html

[R28] 浮点运算
来源：http://dali.9152youxi.cn/Article/details/gtjgsjewbd.html

echo "scale=2; 10/3" | bc
来源：http://dali.gzhubu.top/Article/details/gtrmtauolz.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtngbacrlz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtugdbwxps.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtmqyeervw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jiagoushi.top/Article/details/gtshetyvim.html

[R31] 局部变量
来源：http://dali.zhixingplan.top/Article/details/gtstnzhawx.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryuznhey.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtzkqmuyem.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gttmlhtjtu.html

[R33] 捕获错误并提示行号
来源：http://dali.xylfe.cn/Article/details/gtrejysvlp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtyxkgbuzo.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtpgjnxacl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtoapehxvd.html

[R35] 后台执行并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsyykntd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.bjfxy.top/Article/details/gtrosqqsxm.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtizyxugbn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfihoqtqe.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtcodcmyku.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gtwmkwkkmu.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gttbjflogc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.iojbl.cn/Article/details/gtxpznqnms.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtpqrarrmq.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtnwutohgq.html

[R40] 追加写日志
来源：http://dali.cucudq.cn/Article/details/gtoxynfemd.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtyekeqxbv.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtqypewhki.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtzhgjqwfz.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtmqplnqvd.html

wc -l < a.txt
来源：http://dali.yonumen.top/Article/details/gtkbzwtesj.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtppmyrjuy.html

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtezyfivpa.html

[R44] 按修改时间查找
来源：http://dali.havefunace.top/Article/details/gtorvdtnam.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtxlwgcnsg.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcccjfvb.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtkttomfxd.html

[R46] 递归替换文件内容
来源：http://dali.shangyingyoupin.top/Article/details/gttbfkfvlk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtaiqfprtj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gtogfsifau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtueltvbnh.html

[R48] awk 取指定列
来源：http://dali.chenjidiqi.icu/Article/details/gtfzfhzhjc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtrkvbhuox.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtdixjcsat.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtmhcmbovf.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtdfwwtiwe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtnutpjbrj.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtsshlzzme.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtvrxqwrdy.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gtwybyntsk.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtvebgcxqj.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtcvlzfxxr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtvlxdvggp.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlzgpplw.html

diff a.txt b.txt
来源：http://dali.ivvv.top/Article/details/gtlqyrnknb.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtznhtwbnr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtzzqxncic.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gtaiaelxea.html

scp file user@host:/path/
来源：http://dali.kuanghao11.cn/Article/details/gtgpkcisny.html

[R57] 远程执行命令
来源：http://dali.haohaochexian.top/Article/details/gtafqsifwf.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtjhafffto.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtsnvoepni.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtanepkwms.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtxmfousyn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtgvvroagx.html

[R60] 只看 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtlsgulvuk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtzlgvikzs.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtfrhbokxj.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtljnozvhi.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gtmeaimkox.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gttbuqtesl.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtxcxviyij.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtabxueeka.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gteozursgh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtxczjfmpv.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gttqycdkui.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtlyphctvv.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtnshmfmxx.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtbxgkvgwq.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtuahyqyol.html

openssl rand -hex 16
来源：http://dali.yanxiufei.cn/Article/details/gthaatnmmg.html

[R68] 计算文件校验值
来源：http://dali.hywenlv.cn/Article/details/gtrgwulkdj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtigrddhhh.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtczukjcnr.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtyxaxavci.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gttnfpemgo.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtjubrdfaf.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtgbgqcflr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.meibo888.top/Article/details/gttdbxcbqr.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtmvsehzcl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtrtbawbmj.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtpaezngof.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtjufbacdj.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtathpiajw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtaigdeirt.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtelbyabwq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dianchejie.cn/Article/details/gtggfnfskq.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtxiwyvsxf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenzaomai.com/Article/details/gthyuojqbj.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtkgsamngb.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtfpsmvzfj.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmmtntxy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gtanksbryo.html

[R79] 解析命令行选项
来源：http://dali.aibaodan.cn/Article/details/gtimzhftjq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtebiqdzvl.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtxgsvbkrp.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtcieiaqfq.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtljygdlbi.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gtbnkzekty.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtditpexdx.html

[S01] C：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtcqdavcwk.html

#include <stdio.h>
来源：http://dali.cheryme.top/Article/details/gtbpcioqvi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtiiajjauv.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtuhbyoenk.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtkamvwurj.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtbgvapgtv.html

int x; scanf("%d", &x);
来源：http://dali.hfpthk.cn/Article/details/gtbjkomicm.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtyoywscla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtylpknvsh.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gttmiihcpg.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtgoluwjfm.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtaecrxcho.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtpczuybnc.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gthgjvoswe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtwolrxuaz.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtqhixalab.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.guannengcc.top/Article/details/gtabkillgm.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtdmizbkts.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtjwpeegpt.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtthahtydl.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtogawikxm.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtatjfabhu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtvgfdnicq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtuzrpecpl.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtgqxjfexb.html

[S12] C：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtcbcfxygd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtfqtdlkhs.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtyronxcpb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtiytknkue.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtpjmyrtnr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtnenqihhd.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtpggmgqxg.html

(double) a / b
来源：http://dali.wangshuangyany.cn/Article/details/gtgndeeirs.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtgtkhzbma.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcaudwewm.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtvahjwiqj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gteznykcwc.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtagwkncje.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtngxqwrtz.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtbftspzjs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtrqfboyrg.html

[S20] C：二分查找
来源：http://dali.shangyingyoupin.top/Article/details/gtydkdavme.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gttribezaq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gttsffnour.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nanxuanxn.top/Article/details/gtjbpvypzx.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtkbstdqkp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtsktpfrvn.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gttbmexvhv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtdplqfgvc.html

[S24] C：获取本地时间
来源：http://dali.xuanzx.com/Article/details/gtefwmvxsw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtvxpvilfg.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtcoeuvupa.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gthpaohayk.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtcikinofk.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtvuushmkj.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gtvxflqfor.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtacqhzpds.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtoclkyddl.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyogzkodv.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtkhqdlgwz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtfhkhxpaj.html

[S30] C：头文件保护
来源：http://dali.yonumen.top/Article/details/gtpxznojen.html

#ifndef X_H
来源：http://dali.yj20258.top/Article/details/gthkuocyjr.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtygsqepcj.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtsvxkqyvd.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtlkcawbwy.html

#include <iostream>
来源：http://dali.haohaochexian.top/Article/details/gtdtzndrzx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtridbdxrm.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtppehggce.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtytccauvc.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtltbqkspw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jianghu66.top/Article/details/gtnvyrvjej.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtpirognob.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sufxvd.cn/Article/details/gtdllzhviz.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtsqdvgyiu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtlxscuoyw.html

[S36] C++：unordered_map
来源：http://dali.jlsjyb.cn/Article/details/gtjtcyypim.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtlqvvgfqz.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkxbents.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtrblyeoxm.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtebnteftk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtakshqmel.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtljzezszm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtwfnzfzfo.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtrouoskma.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtvtgotkon.html

[S41] C++：类与构造函数
来源：http://dali.shuidangran.top/Article/details/gtocytlhkj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cqqwz.cn/Article/details/gtgbozzhkb.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtbmeeghky.html

class B : public Base { public: void f() override {} };
来源：http://dali.hysaishi.cn/Article/details/gtiouikhju.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtxahtmwed.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gttcesqeat.html

[S44] C++：引用传参
来源：http://dali.jianghu66.top/Article/details/gtzwlzdrei.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtlghvdfoj.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gttbrkyqsp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtzeqinige.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtofcyucwg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtsmdtyzyn.html


<!-- 参考信息 -->