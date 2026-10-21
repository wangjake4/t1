代发 wailian999

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtqvgnhkde.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ybcxt.top/Article/details/gtlolowuxt.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtnbolsijl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtcrnepfhi.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtrguhszhc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtgjkzxpre.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtzhmxukkm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gtpbxavczs.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gthsrxtbop.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzwbvzohe.html

[Q83] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtgnxarlag.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtntqmtvfm.html

[Q84] 去除首尾空格
来源：http://dali.tian-w.cn/Article/details/gtpnbtudyo.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtsddxsbhe.html

[Q85] 数值取整
来源：http://dali.aizwys.cn/Article/details/gtqeqkmvpg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtkqjgytsd.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtyzsqugsg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gttzsgopkp.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtzqjwhjqk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtgswxfucl.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtjlrvnebr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.feifeiyinyue.top/Article/details/gtqmaslllt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtnxpawogp.html

[Q89] 判断表是否存在
来源：http://dali.svipenyu.cn/Article/details/gtebjbsoug.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtnicirjpz.html

[Q90] 生成序号列
来源：http://dali.guannengcc.top/Article/details/gtmklzmqvb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gtowkglqej.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteyoqnuka.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtmelijkxz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttjofluif.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtzeksavpb.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtrnpovhmj.html

set -euo pipefail
来源：http://dali.nwbrower.top/Article/details/gtqmjmfudq.html

[R02] 变量赋值与使用
来源：http://dali.sxryk.cn/Article/details/gtmaoxafji.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtntzsmptm.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtzmtisoci.html

readonly PI=3.14
来源：http://dali.chenlongwang.top/Article/details/gtxypqlnqw.html

[R04] 位置参数
来源：http://dali.yongpay.top/Article/details/gtugkvotor.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.kuanghao11.cn/Article/details/gtcxpfgagm.html

[R05] 参数默认值
来源：http://dali.quarkkingdee.top/Article/details/gtwqmphgbd.html

name="${1:-default}"
来源：http://dali.yj20258.top/Article/details/gttocrcgxw.html

[R06] 判断命令是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtbafvvqdm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqkginqtk.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtwpnyhawb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtprzizern.html

[R08] 数值比较
来源：http://dali.xziqi.cn/Article/details/gtzskqccdy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtcxrpnrsf.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtpyrdfjwa.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtryxljzlh.html

[R10] 正则匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebhpboct.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gtiimorjjb.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtlvkqghfw.html

case "$1" in
来源：http://dali.quarkkingdee.top/Article/details/gtbbfweyol.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfzolnff.html

stop)  echo "停止" ;;
来源：http://dali.zdqjudy.top/Article/details/gtuxmrhbmi.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gtuxkpghwk.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gtdvcaukef.html

[R12] for 遍历文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpphglxgn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hammf.cn/Article/details/gtwxdfmerl.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtzktmekdf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtuqdzzzud.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtnzrbrwbw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtacrpuodq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gteykbmdos.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtejvkwgcq.html

[R16] until 等待条件
来源：http://dali.fzhhl.top/Article/details/gtmsthmfda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtfzcdsfjt.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gtzasybqjw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtgjvjshlm.html

[R18] 遍历数组
来源：http://dali.andypj.xyz/Article/details/gthawazxhk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtdlifmgqo.html

[R19] 数组长度
来源：http://dali.cheryme.top/Article/details/gtddqjcxzh.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gthyyryqzk.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtnwncakyq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gotoacloud.top/Article/details/gtvwrxfzss.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtgodvgiee.html

echo "${#s}"
来源：http://dali.meibo888.top/Article/details/gtijxilrvw.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdeqsoqq.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtlkfuwqfw.html

[R23] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtbbsdbhrz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gtmpqahmwo.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtyflomtac.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtczfnfjxy.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtdowcnlhv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtmdfugeiy.html

[R26] 命令替换
来源：http://dali.gogol.net.cn/Article/details/gttnnuafms.html

now=$(date +%F); echo "$now"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajwjrkhf.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtanzbikla.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuvfqrhj.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtpyzcdbaa.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gttsqrosmb.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtirzzwsyi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgufenzy.top/Article/details/gtadoitqvv.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtdkcifxsp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gtxzlatafm.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtsrdyqrdc.html

f() { local x=1; echo "$x"; }
来源：http://dali.yueranfly.top/Article/details/gtmcjzzpro.html

[R32] 参数个数校验
来源：http://dali.jqgfzy.top/Article/details/gtnboyeqon.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gtqbtpqvnm.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtaqhgftme.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gthrblndyi.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtchxlusbz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbykpakq.html

[R35] 后台执行并等待
来源：http://dali.aizwys.cn/Article/details/gtyalfmioh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtpoqltxzs.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtszvtumvk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gtlttcaivi.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtltosyvsw.html

files=$(ls -1)
来源：http://dali.hysaishi.cn/Article/details/gtvozslhxf.html

[R38] 管道串联
来源：http://dali.gotoacloud.top/Article/details/gtfhbgmuwl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtygyvnnos.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gtxkakgvdu.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtvpfwfqlm.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtdfjekexh.html

echo "log" >> out.log
来源：http://dali.quarkkingdee.top/Article/details/gttuorxnaz.html

[R41] 丢弃输出
来源：http://dali.bjfxy.top/Article/details/gtnloriuba.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gttfjnpfif.html

[R42] 输入重定向
来源：http://dali.xinyue.icu/Article/details/gtrwitcyxo.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtnfbzczfp.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtruyiewdc.html

find . -name "*.log" -type f
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkhjwpet.html

[R44] 按修改时间查找
来源：http://dali.yuxming.cn/Article/details/gtdjevmrxl.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gtjlwhnggk.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gtlsmobyku.html

find . -name "*.tmp" -delete
来源：http://dali.xinyue.icu/Article/details/gtcthcsvlp.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzhjdpdn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtoyxwyjsj.html

[R47] sed 单行替换
来源：http://dali.yuanzhike.top/Article/details/gtyxyztxng.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gthphhcivv.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtyxyskxhl.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gthoksxfhj.html

[R49] awk 带条件
来源：http://dali.hfpthk.cn/Article/details/gtbxexpzkl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnqzz.top/Article/details/gtzhtdemsr.html

[R50] awk 求和
来源：http://dali.meibo888.top/Article/details/gtbwcqijwo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtemfmjnnh.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtijsifmlw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtbfsxyvib.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtfzttjgng.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtohrehqfl.html

[R53] 查看文件头与实时尾
来源：http://dali.shuidangran.top/Article/details/gtgsuwmrse.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gttevzhshe.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtfilezdnq.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtkmsmmbzs.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gthlvvkibg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtsbjibinf.html

[R56] 远程拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtaknojvea.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtjbbzkpvq.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtynuuwewy.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtiyauudwt.html

[R58] 下载文件
来源：http://dali.guannengcc.top/Article/details/gtsagavxbw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gtbaduuhnb.html

[R59] 发 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtuorxutqx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtkurvvkpp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtcbubklvb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gtnzsuhgii.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkoqsktd.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtquznmqsr.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtufzbhcbe.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtzejebzvx.html

[R63] 内存与进程
来源：http://dali.0kj1m.cn/Article/details/gtqdnsplxi.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtxgmbwxsd.html

[R64] 结束进程
来源：http://dali.sxryk.cn/Article/details/gtylcxptwq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jyoumei.cn/Article/details/gtdpzwuiph.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gthhpyhwst.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gzhubu.top/Article/details/gtdmermgsy.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtbozshlll.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtoogszcae.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtkanlknac.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtuqajbnuf.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtxancbgfj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cdnleiting.top/Article/details/gtibopcsek.html

[R69] 生成随机密码
来源：http://dali.gaohongyu789.top/Article/details/gtaybnfszy.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gtcjuehedt.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtqpvwwarn.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtzlvxibnw.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtcgovxuza.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtotzxujca.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtdwxafcqt.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtuyvoqcww.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gtjvtoensl.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gtrbmcvvsr.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gthjnyzojr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtogxopeua.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtqtvoggdf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtkjakvqgn.html

[R76] 使用临时文件
来源：http://dali.fzhhl.top/Article/details/gtjgzsupmw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtupzrekfp.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtzxqlqoyk.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gtlqvamxbc.html

[R78] 交互式菜单
来源：http://dali.mhx1999.top/Article/details/gtdnitzjjt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtxuthlogp.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtsrqchkmo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtzlgcoepm.html

[R80] 查看脚本执行耗时
来源：http://dali.cashguo.top/Article/details/gthkthxrop.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtmmymgpgi.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkgzhvhvu.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gttvuwpsmn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gteltppcdr.html

[S01] C：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gttkwosuyx.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwibwocb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuipfhlh.html

[S02] C：变量与格式化输出
来源：http://dali.shzxlz.cn/Article/details/gtfmntfzpv.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtowbrwhep.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gtkrbaunwp.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtvhbkucks.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gteephtrse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtrlfkepph.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtzntcbfsw.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gtbabmjdjm.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gttdnqtgak.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtqrvfqgti.html

[S07] C：数组遍历求和
来源：http://dali.xuetiantiany.cn/Article/details/gtkyeaexzy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtezgedjxv.html

[S08] C：动态内存分配与释放
来源：http://dali.xziqi.cn/Article/details/gtyhpjwtby.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gtcfgibbgg.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtyulaqcms.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtlwhenjhz.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtxvwvrffx.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtcfirrdyj.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtkplcmwip.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ybcxt.top/Article/details/gtyxqaftpk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtrhehyjpm.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtnrowpzbx.html

[S12] C：写文件
来源：http://dali.wangdashe.top/Article/details/gtlzytutml.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtylatnesz.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtylhojwzq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtdeuwldtg.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtudambsaj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjilrcej.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gtcavpkykh.html

(double) a / b
来源：http://dali.vqdsnc.cn/Article/details/gtpcagzmez.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtrghbjxuc.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtxojywsyr.html

[S17] C：安全拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtmkathasg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.dianchejie.cn/Article/details/gtdwcskupq.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gttbnyuvql.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtvnygbvgd.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtwljaiqyj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtjzxahwue.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtsvuumdbr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtpxlqhkhj.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtlfkojzge.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtwovcofpm.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtsnwxxlih.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gtdatezovz.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gtvivpkozf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxuanxn.top/Article/details/gtqdkjgtsc.html

[S24] C：获取本地时间
来源：http://dali.daria6918.cn/Article/details/gtnociisge.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtvyjugibz.html

[S25] C：内存拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtgihjpuft.html

memcpy(dst, src, n);
来源：http://dali.zdqjudy.top/Article/details/gtcfkhtnnj.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtzkmqfpee.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtmudvbgvt.html

[S27] C：定义常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevytwfve.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtwnvumuua.html

[S28] C：静态变量
来源：http://dali.yj202588.top/Article/details/gtfoybdeuo.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gttjvpxzet.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtppqcxpit.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtnykpondd.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gtnriaowqt.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtkwprwzxw.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtqfvpzapv.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtuezdotmh.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtrmvabkek.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gtngzhpwfd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtpmlfbher.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtmontuznf.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtsbrfarcm.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtqiheprnc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnqzz.top/Article/details/gtvwqozoas.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gtqkiyweij.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.iojbl.cn/Article/details/gtuohzlzzl.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtktaxchoi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtosvptqvt.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtxnpivptp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtnvwxiuql.html

[S37] C++：set
来源：http://dali.hnqzz.top/Article/details/gtjbxztbng.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcscozvn.html

[S38] C++：排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndvsmepv.html

std::sort(v.begin(), v.end());
来源：http://dali.sxryk.cn/Article/details/gtbhqhigoz.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtefuuoxah.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtyfafjely.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtqudrssru.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gtgtszwydh.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gttmwaswip.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gtyffrzpln.html

[S42] C++：继承与虚函数
来源：http://dali.gzhubu.top/Article/details/gttzgaxkuy.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtbexdryqg.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtwcadqnxy.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtwkcimumz.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtxjbzeujg.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gteqilfkmv.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtxqhpqanb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtcvezzlru.html

[S46] C++：函数模板
来源：http://dali.kuanghao11.cn/Article/details/gtdldbxqrw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqribllfl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrgighwg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtdutnqadm.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gthxtldgsb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtpprnqnqd.html


<!-- 参考信息 -->