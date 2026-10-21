代发 wailian999

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtsrjcomax.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtwnfejtss.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gteawlrlbw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cashguo.top/Article/details/gteecafekc.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtpihhdrbd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtsdcasfjw.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtrwcuwmtj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtselhabcl.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gttrthszmi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtiicxupfk.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtrqkbkndb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtexfzrrxw.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtxmxnlgcl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtvqjzmmwy.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtmgcrwaaw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtyzggjvct.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gticscicip.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtlcofcnrb.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gtunqkwcxb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtakcljvhp.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtdbfgmyse.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtzndibzqa.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtuimuyucf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gtqtxswgwd.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtksamxnqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtpexghwwt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gthdrzrqim.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtfjlnfuot.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yvedp.cn/Article/details/gtknacjrlr.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gtufxbovke.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtkjqfhcev.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqcsvhrcm.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtxjnvooiv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjxucsohd.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gthmsnpwxr.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtflksaeia.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtihmhnrkl.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gtswrtmuuv.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtofdmaarg.html

[R03] 只读变量
来源：http://dali.yj20258888.top/Article/details/gtpxauwpyc.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtompuhzys.html

[R04] 位置参数
来源：http://dali.ydzc1.top/Article/details/gtvgxegomz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtetupyjln.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtcsxostqg.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtkftntuib.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtgmpdsqex.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtiixmhril.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqxamfvmp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtohcfnxjg.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtbolujmpy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigufen.top/Article/details/gtjvqzdipn.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtupgwxakn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gtisnxrahj.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtrlacergx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gttkuzmfnv.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtxhsjkvud.html

case "$1" in
来源：http://dali.daxiang520.top/Article/details/gtldzrgyuf.html

start) echo "启动" ;;
来源：http://dali.hnqzz.top/Article/details/gttnzcgdzm.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtbuwfkred.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtulhbmhsv.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtrqaeoein.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtmjycvcwu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.feifeiyinyue.top/Article/details/gthfvqtbya.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtmzjoanfm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtsdydihai.html

[R14] C 风格 for
来源：http://dali.wangdashe.top/Article/details/gtnsjdkotq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtubphuznf.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtqctmlwct.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gtytorxvia.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtumluntqc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmkngkxq.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtcmwaqxgf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cucudq.cn/Article/details/gtwgcdcooj.html

[R18] 遍历数组
来源：http://dali.zhoulong.xyz/Article/details/gtywukuufj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gtplkqbfzp.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtslywhdyy.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gthwakntgu.html

[R20] 关联数组（字典）
来源：http://dali.xuanzx.com/Article/details/gtnwmovvxs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jiagoushi.top/Article/details/gtobflbcut.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtxulpboyx.html

echo "${#s}"
来源：http://dali.haohaochexian.top/Article/details/gtepyxdwfi.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gtswdtqpbw.html

echo "${s:0:5}"
来源：http://dali.sxryk.cn/Article/details/gtvnmnvemt.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtoofnccfr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gtxrdoniyq.html

[R24] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtzpmpzogu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yangfankeji.com/Article/details/gtxouqpbbm.html

[R25] 去后缀 / 去前缀
来源：http://dali.fzhhl.top/Article/details/gtvsmhsnwb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtgawlelpn.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtdszngqiv.html

now=$(date +%F); echo "$now"
来源：http://dali.tianlin.xyz/Article/details/gtiokzwssw.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtvsizrwsa.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtaybfpaly.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtwjpsxgee.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtvlcrrtip.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtbynzpcua.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.9152youxi.cn/Article/details/gtcgwpmfja.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbsriydz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gtubjglynh.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gttzgfvcyg.html

f() { local x=1; echo "$x"; }
来源：http://dali.kuanghao11.cn/Article/details/gtkfeecujp.html

[R32] 参数个数校验
来源：http://dali.yueranfly.top/Article/details/gtgjuezlbh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtgeylpjun.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtcscpwnpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.redwolf501.top/Article/details/gtbasnkidm.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtvaxhjxpl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtozzufyse.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gttzavuqth.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aizwys.cn/Article/details/gtimjobuyp.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtnerlsckh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hfpthk.cn/Article/details/gtbtnxjhmd.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gtxrelytyb.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gthcoqcwtv.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtlgfxfvai.html

cat a.txt | grep -i error | wc -l
来源：http://dali.mhx1999.top/Article/details/gtzahynetv.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtnjmxotok.html

cmd > out.log 2>&1
来源：http://dali.wangshuangyany.cn/Article/details/gtqwgpzjay.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtnaeeatrr.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtsiwdgefr.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtdouxgygb.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtyhosukuh.html

[R42] 输入重定向
来源：http://dali.c1oappe.top/Article/details/gtzrvunxlx.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtnlmuakfc.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gtflouxaht.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtqinkgkhu.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtatulyrxn.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gtbjkkfljo.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtyvqgrzad.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtmcdjlend.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gteaxscbmj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtcbdnnztn.html

[R47] sed 单行替换
来源：http://dali.hnxiangtu.top/Article/details/gtsqgdheke.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtylspifym.html

[R48] awk 取指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtrfiuyxdy.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtwzwxpfek.html

[R49] awk 带条件
来源：http://dali.bjfxy.top/Article/details/gtzhpqdgcu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gteiiorzef.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtkrlzflmo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.meibo888.top/Article/details/gtaidlbiqe.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtwwtzuaen.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gtyeawtbcx.html

[R52] 统计行数
来源：http://dali.nanxinkj.top/Article/details/gtvgieekvz.html

wc -l a.txt
来源：http://dali.tanke756.top/Article/details/gtmrhbaznt.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gttxgtpgln.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ppjwa.cn/Article/details/gtiioclrbl.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtbblcrzmm.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtuciaqdpi.html

[R55] 压缩与解压
来源：http://dali.gogol.net.cn/Article/details/gtcitshilx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtrwawviuz.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gtjzvkantd.html

scp file user@host:/path/
来源：http://dali.fengsongda.top/Article/details/gtmuszcgkm.html

[R57] 远程执行命令
来源：http://dali.tianlin.xyz/Article/details/gtepypokxi.html

ssh user@host 'uptime'
来源：http://dali.yongpay.top/Article/details/gtgxbtxibp.html

[R58] 下载文件
来源：http://dali.haohaochexian.top/Article/details/gtfmvnfnjq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtfhjvlieq.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtygctptvk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gtsytwjoav.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtsqsdrsqh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtbcwbtcjw.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gttxfcmzmp.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtlcxmswoo.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gtdmeiidku.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtygoyjicq.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtealueqdu.html

free -h;  ps aux | grep nginx
来源：http://dali.cdnleiting.top/Article/details/gtsvripczi.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtojzycuja.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkdjgkwt.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtoqcijlxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shangyingyoupin.top/Article/details/gtppnncyfl.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gticcornwu.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtxmhxgfvz.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gtyvnvpjxe.html

openssl rand -hex 16
来源：http://dali.guannengcc.top/Article/details/gtxdngmbhq.html

[R68] 计算文件校验值
来源：http://dali.nanxuanxn.top/Article/details/gtqjycvltp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtkmkosagw.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtttsuiait.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtnsvoqoww.html

[R70] 时间戳与互转
来源：http://dali.sxryk.cn/Article/details/gthmvtxvlq.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtiamyhxpc.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gttkxhiggp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtcpomzkwd.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtyszemwqp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sweek.top/Article/details/gtnqqgsigv.html

[R73] 分割大日志
来源：http://dali.jianghu66.top/Article/details/gtwzcvdkwc.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gtpgwufuyy.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtkqnyqatv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzvpihqt.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtilmtysjl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtpxfjemlp.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtgahwwsoc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtxppbuhta.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gttvclaown.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtjzaljcmx.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtyngzxzko.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gthfopcsru.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtdrgdsnil.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gttfzjojzm.html

[R80] 查看脚本执行耗时
来源：http://dali.ydzc1.top/Article/details/gtcloihlka.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gtwrqsdzhg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvahpwtwj.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gtrtvpnbua.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxbpuuifk.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtayxfoghy.html

#include <stdio.h>
来源：http://dali.jqgufenzy.top/Article/details/gtstqdkaav.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtjcmohiys.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtpcgujosv.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gtbgipfrfy.html

[S03] C：读入整数
来源：http://dali.zycfv.cn/Article/details/gtqpmdwmxj.html

int x; scanf("%d", &x);
来源：http://dali.vqdsnc.cn/Article/details/gtprisaqhz.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gtgkvvrmpi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuctyrewf.html

[S05] C：字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtyqmgbkci.html

strlen(s)
来源：http://dali.zhengqikj.top/Article/details/gtbliyamnp.html

[S06] C：字符串比较
来源：http://dali.chenlongwang.top/Article/details/gteepajyki.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtqbxvbqwf.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gtzmtyiawe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtzceesnhb.html

[S08] C：动态内存分配与释放
来源：http://dali.cucudq.cn/Article/details/gthrshxibi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gtxmyltgug.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavzsdqfu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtmijesdws.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtekvtlxsk.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gttepbuheo.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtxnkesyea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yvedp.cn/Article/details/gtndegkcct.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.nanxuanxn.top/Article/details/gtkzsiqili.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtzvuzunjj.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gtaemmnjyk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtyshzzsni.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtecslimuv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gtxjsmvxcn.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gtdennzoak.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtryrvehja.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtbshtcavn.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gthjmjfjsd.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtydeqglpz.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtvfofxrbo.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtndpkjmtp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtbnjffeat.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtwjzowete.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtcicyysbs.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtxtlmxoms.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xziqi.cn/Article/details/gtercdvyfm.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtrowucahu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtvctjdzvf.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtkzrfytuy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtyskbyefv.html

[S22] C：字符串转数字
来源：http://dali.feifeiyinyue.top/Article/details/gtnudswqip.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtpqglgyjq.html

[S23] C：随机数
来源：http://dali.hysaishi.cn/Article/details/gtzyhnqwtp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gtnbwarkiu.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtyxrhnxro.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gttshsrxhe.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtnxdnudjw.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtevxgsrbn.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtqwcmgzyl.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gtlvxqezin.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtrtfojlcr.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtdyoxbiii.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtgufasigw.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtantxxsfl.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtnbxrmfyb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtypbygadw.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtvvdzfbao.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtncptpeqy.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtjshkbnbd.html

#endif
来源：http://dali.guannengcc.top/Article/details/gtrbmdxfdp.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gtrnzqsysf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gtbdvamrbr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gtfjersjkb.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtegctjmuy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gtlqolmoit.html

[S33] C++：vector 增删
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlemuzmta.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtjlnormka.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtdvhxwccg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gtkdnivhen.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtszlzytww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtkonjslrs.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtcgmpcfch.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtivvvrsse.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gtivnknejd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtnnjyqnbv.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gtwadfjeyd.html

std::sort(v.begin(), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtkqzfqlwx.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtdxsckexq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtefbrfvtn.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtieevmjje.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gtowkqxqcr.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtbzenvjxg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtsnapwkrh.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufqjusey.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gtzpjxbbif.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gthqiehaob.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtgydjqxvf.html

[S44] C++：引用传参
来源：http://dali.dashuyun.cn/Article/details/gtiolrzmrh.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtadmzmzny.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtsloowcst.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yangfankeji.com/Article/details/gtxgtawibg.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtvcaibjvl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtabpgygvs.html


<!-- 参考信息 -->