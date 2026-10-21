代发 wailian999

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtycomuspy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtrmjfmmsa.html

[Q81] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtrvlafeoc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gtggtyrpuw.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtsbqddtjl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtepodmncp.html

[Q83] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtghhwynpb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtrbqyuldm.html

[Q84] 去除首尾空格
来源：http://dali.gzhubu.top/Article/details/gtwxtaecze.html

SELECT TRIM(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtrioudkwy.html

[Q85] 数值取整
来源：http://dali.zdqjudy.top/Article/details/gtkycaqxww.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjgacdav.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecqjuxye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gtvjqrjfze.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtnfyxflix.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gtapytayce.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxuanxn.top/Article/details/gtcwzrhpvc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gthzcztigi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtzigqedyi.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtgsfnojbh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtmqcjzala.html

[Q90] 生成序号列
来源：http://dali.cheryme.top/Article/details/gtcpqscytw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtsauyqqdq.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtacajgrtc.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtwucdnnfr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtywauisgd.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtpgufeqte.html

#!/usr/bin/env bash
来源：http://dali.c1oappe.top/Article/details/gtzpsjrqgr.html

set -euo pipefail
来源：http://dali.jinqigfzy.top/Article/details/gtcxqcjrwv.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtwztibibq.html

name="Tom"; echo "$name"
来源：http://dali.cashguo.top/Article/details/gtmmikpaaw.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtwbzqjlsa.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtfrkjcpeb.html

[R04] 位置参数
来源：http://dali.0kj1m.cn/Article/details/gtccyabhuw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtyoguaxjs.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtoxotrgnk.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtxcwhlcqk.html

[R06] 判断命令是否存在
来源：http://dali.svipenyu.cn/Article/details/gtuinpwumq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtkorwlwzl.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gturdulmzs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtosqbjtxo.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtnuvwygnh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtmkbkzolj.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtxfwbekcs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gtonyusfos.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtqlvkmkam.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aibaodan.cn/Article/details/gtdjtnujmn.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gtybrjonuo.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gttvhlkdgp.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtzxitfroa.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gtmgdbcjmj.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtdqcnlllm.html

esac
来源：http://dali.wangdashe.top/Article/details/gtvahebmkr.html

[R12] for 遍历文件
来源：http://dali.cucudq.cn/Article/details/gtnyjdksyq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtfwdceoin.html

[R13] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gtvicyslcu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gtcnjedbhe.html

[R14] C 风格 for
来源：http://dali.gogol.net.cn/Article/details/gtlvnvsbfu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtzgnquosw.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtmlkrkeej.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtimfirsau.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gtrsndaaga.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtmdcbmzup.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtswwrzjec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtamumcxjz.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtjeivrykq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtgphqnqfp.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gteancbztt.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gtprsrorwo.html

[R20] 关联数组（字典）
来源：http://dali.zhiwuduotai.top/Article/details/gtgnlsxcis.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zdqjudy.top/Article/details/gtsnevbxex.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtxikrpnvq.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtskprofll.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtmftsqmki.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gtniofcsce.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtmkbcsnfd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxinkj.top/Article/details/gtflcvvluu.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtzhgrkjad.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtdbyjvkid.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gtkggawkqo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyurmdpzh.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtdmwmfegl.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtkmvaonad.html

[R27] 算术展开
来源：http://dali.sufxvd.cn/Article/details/gtcaekeewo.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtnndtyizv.html

[R28] 浮点运算
来源：http://dali.daxiang520.top/Article/details/gteagckvrx.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtfumtmmil.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gttkimwfmx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhongyouzk.top/Article/details/gtuythfddc.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtchqrbbyt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtgxwghfac.html

[R31] 局部变量
来源：http://dali.daxiang520.top/Article/details/gtbcfcmjgj.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtxtjkktve.html

[R32] 参数个数校验
来源：http://dali.cashguo.top/Article/details/gtkkhgtdro.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtrkqfrlvv.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gtrdpiebhu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyylaoco.html

[R34] 退出时清理
来源：http://dali.hongshengwenyu.top/Article/details/gtpxsfeoru.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtcktqjsmt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtvtkncrgb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ivvv.top/Article/details/gtrjzslpvv.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtopuyvcia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtrnnjidpm.html

[R37] 把输出赋给变量
来源：http://dali.pengpengdd.cyou/Article/details/gtglulxswa.html

files=$(ls -1)
来源：http://dali.shzxlz.cn/Article/details/gtttftshqc.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtgvmnoweb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtdbqackfi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtjvgrpaiw.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gthjtuxqeg.html

[R40] 追加写日志
来源：http://dali.yj202588.top/Article/details/gtvotzvogc.html

echo "log" >> out.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtfytpsgnl.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gtmhccdpaa.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gttepjyogm.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtsojqvidy.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtvuscfuwv.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtbiivrjle.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gthtiaofbg.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtqilwldob.html

find . -mtime -7 -type f
来源：http://dali.andypj.xyz/Article/details/gtrixbxsaz.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtuvqgczol.html

find . -name "*.tmp" -delete
来源：http://dali.birdmap.top/Article/details/gtouxwujps.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtpuzbikup.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jianghu66.top/Article/details/gtnkgokeug.html

[R47] sed 单行替换
来源：http://dali.chenjidiqi.icu/Article/details/gtzpplhdqd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xinyue.icu/Article/details/gtumacspqq.html

[R48] awk 取指定列
来源：http://dali.vqdsnc.cn/Article/details/gtbjyfrult.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtfyzgegnd.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtedxrtugo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuetiantiany.cn/Article/details/gttdjrxcug.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtwhauqpwt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtpozkrkzy.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtgkimtxuv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtpfcglsja.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtdgaosych.html

wc -l a.txt
来源：http://dali.dianchejie.cn/Article/details/gtssxdeezb.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtuiocjjcs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtngsjhzmv.html

[R54] 比较两个文件
来源：http://dali.dianchejie.cn/Article/details/gtbesgvajp.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtvtllqsyq.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gtscrludli.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtmnuoecrm.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtysbvtjzg.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtmdrgxwxh.html

[R57] 远程执行命令
来源：http://dali.gotoacloud.top/Article/details/gttxhmwclt.html

ssh user@host 'uptime'
来源：http://dali.cucudq.cn/Article/details/gtjnsvyyzx.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtccfaaowq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtblckgjay.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gthagbouqc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gttjravnly.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtspoksbvn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gthyhtcxbm.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtpfcncovx.html

df -h;  du -sh *
来源：http://dali.cheryme.top/Article/details/gttznqzxte.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gthgrendui.html

du -ah . | sort -rh | head -10
来源：http://dali.shzxlz.cn/Article/details/gtgevbglvb.html

[R63] 内存与进程
来源：http://dali.yvedp.cn/Article/details/gtwgkwfxfn.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gtzocnmwfm.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtnxixyuhl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gtvalklzok.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtpvuxjhka.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.316326.xyz/Article/details/gtkgwinnih.html

[R66] 定时任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjmyzayx.html

crontab -e;  crontab -l
来源：http://dali.aizwys.cn/Article/details/gtzpgyqksi.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtvwltxdtq.html

openssl rand -hex 16
来源：http://dali.zdqjudy.top/Article/details/gtsjhghyzu.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtdlepifjf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.svipenyu.cn/Article/details/gtwbsylsfj.html

[R69] 生成随机密码
来源：http://dali.zycfv.cn/Article/details/gtibidprtd.html

head -c 16 /dev/urandom | base64
来源：http://dali.jlsjyb.cn/Article/details/gtknskvfub.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtawkdxkrg.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigfzy.top/Article/details/gtljavchuk.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtqnoctagz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gtlhvqaafw.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdahqeuse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtdibmgrvd.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtafsamaux.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtfgvkyeeb.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtxrobrugn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guowangkeji.top/Article/details/gtdvdmltps.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtyljtrpxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtbkwpcugx.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gteidcafme.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ppjwa.cn/Article/details/gtqgocoqjc.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gteadlskod.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtytgfsqrt.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtpjgwtlyc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtycxfxanc.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtlgugoczi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.feifeiyinyue.top/Article/details/gtyjbkvfea.html

[R80] 查看脚本执行耗时
来源：http://dali.hongshengwenyu.top/Article/details/gtzypequhd.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gttzgdquhg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxjwmueog.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gtoitaahep.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyjuupbr.html

[S01] C：Hello World
来源：http://dali.tian-w.cn/Article/details/gtywtfwgfn.html

#include <stdio.h>
来源：http://dali.nwbrower.top/Article/details/gtmnjapdti.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuanzhike.top/Article/details/gtqickbwzg.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtmqwbxbay.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtfpaybsnl.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtlbyczxvd.html

int x; scanf("%d", &x);
来源：http://dali.xinyue.icu/Article/details/gtvgmuoeha.html

[S04] C：字符串复制
来源：http://dali.hongshengwenyu.top/Article/details/gttcmseite.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtojflypoq.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtxnpkolyd.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtrqaneddn.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtbfuqdajp.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtkmcdcinp.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gtuopbvvww.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gtgzionujk.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtfwsdnzfm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtvtfpdpkg.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtmrpduyrr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtehltcdrr.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtbskrxfvx.html

int *p = &a;  *p = 5;
来源：http://dali.zhixingplan.top/Article/details/gtppslnycy.html

[S11] C：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtkexvvtdb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gtbafuvnnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxosduxe.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtamgqyief.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtmlnbcbor.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtsxkcemav.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjifmwdx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtrwvobmml.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtnblpnnmw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtxchyojdp.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gtkmznemzs.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtkxgstlea.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtqwybcpyx.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtfwmwzoda.html

[S17] C：安全拼接字符串
来源：http://dali.daria6918.cn/Article/details/gtyggkurlx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gthttewwhe.html

[S18] C：命令行参数
来源：http://dali.guowangkeji.top/Article/details/gtelzrgspx.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtooeacupy.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtvpdaflpd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtodwalpjb.html

[S20] C：二分查找
来源：http://dali.c1oappe.top/Article/details/gtrwrhwcwh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtzkehnoxz.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtwyfzzdtb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbywhgmfp.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtaiymjxas.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtxadtgdrf.html

[S23] C：随机数
来源：http://dali.jyoumei.cn/Article/details/gtykcqjhlj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtupuaxzhc.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gttsezgytm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtfcgrylzz.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gtzdktasyv.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtbkdpmecz.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gtkjoakqgx.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtiwwltokp.html

[S27] C：定义常量
来源：http://dali.gotoacloud.top/Article/details/gtizakxbst.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtwospkvxa.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtcvtpifks.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtalfiaj.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtuireaofj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtsqspmfln.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gtqixtcbos.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtahjgbabj.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gtspqaktdg.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtajrncrxj.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtfqbtnthj.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtesfxcvtt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gttbyuyolo.html

[S32] C++：字符串
来源：http://dali.c1oappe.top/Article/details/gtsveczjsn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtzqsiyrtx.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtiunoroxy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtxhizqccw.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtrmaighjl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtcphjdolt.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtpthxdpzu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gturxqvxaj.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtqncpxhnc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtasapreqe.html

[S37] C++：set
来源：http://dali.iojbl.cn/Article/details/gtbbjypyex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtueqrjizn.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtidxzdvht.html

std::sort(v.begin(), v.end());
来源：http://dali.gzhubu.top/Article/details/gtvxxhagty.html

[S39] C++：自定义比较器排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixoaolia.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtrnhggwlo.html

[S40] C++：查找元素
来源：http://dali.zhixingplan.top/Article/details/gtduuuoodn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtrlnfmods.html

[S41] C++：类与构造函数
来源：http://dali.yuxming.cn/Article/details/gtgqaprbaf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gtgthwnwnz.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gteiiqjhdu.html

class B : public Base { public: void f() override {} };
来源：http://dali.tanke756.top/Article/details/gtaikrsycq.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtyykwjkof.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyccfurz.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gttehvrete.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtzriurpxd.html

[S45] C++：lambda
来源：http://dali.ehwqpu.com/Article/details/gtinjvrwvm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gtehhrmszm.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzifpsma.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarcjyokb.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtoshckrmz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdanagru.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtkiwgnkrb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvajcwzn.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gtztyvswly.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gteigtrrmg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtrpfylijy.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtuhqjjvxk.html


<!-- 参考信息 -->