代发 wailian999

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtystqahaq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gttwmehnxe.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtaewtkwpq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtzpxcxuzh.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtaxdsfmcg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtalwltftg.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gthjrfkpeo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtbpyfsobt.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gtepggxhdk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtwofgbdud.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtmkjtjsvd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtjswojchq.html

[Q84] 去除首尾空格
来源：http://dali.316326.xyz/Article/details/gtmmxdlwdy.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtlusmndkm.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtizvamosc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gtoqxoiarw.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtmkuqlqdf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqphxfugj.html

[Q87] JSON 字段做条件
来源：http://dali.jqgfzy.top/Article/details/gtnzrsrorc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtqzmzqlcp.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtqeefiobv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtxgcuffbi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtsmawshto.html

[Q89] 判断表是否存在
来源：http://dali.chenlongwang.top/Article/details/gtdxqizbgk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ydzc1.top/Article/details/gtiqwemyvt.html

[Q90] 生成序号列
来源：http://dali.sweek.top/Article/details/gttwwfytrx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gtaeevqjsu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyjiuokog.html

R. Bash 专题
来源：http://dali.jyoumei.cn/Article/details/gtsphqufxq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzvvehddn.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtudbywres.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtbvqpzzpx.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtufkrzxnb.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtlkhxbemy.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtomnyrrhy.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtrsefdnlg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtjbhwkmsr.html

[R04] 位置参数
来源：http://dali.xuetiantiany.cn/Article/details/gtyglldcrc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gtbxmttxoe.html

[R05] 参数默认值
来源：http://dali.redwolf501.top/Article/details/gtjeppgsij.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtsbfchfom.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtbdoaomid.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gttvuspiat.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gtjjikiani.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtxzgtttwz.html

[R08] 数值比较
来源：http://dali.xylfe.cn/Article/details/gtoklvavdu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtrazxohgf.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtzrgbjiln.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtcwbxzgla.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtxeqqnrcv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtxhrwabth.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtcfusuhgf.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gttydzxmxj.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtamznttde.html

stop)  echo "停止" ;;
来源：http://dali.xinyue.icu/Article/details/gtmoanndso.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtbktwynoo.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtoadvluuk.html

[R12] for 遍历文件
来源：http://dali.xziqi.cn/Article/details/gtzxibahzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gteyyubtyr.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxidwdws.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gtbdnkafzw.html

[R14] C 风格 for
来源：http://dali.kuanghao11.cn/Article/details/gtumfozjdo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gtqkuunhyp.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtcocvgotl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.pycfn.com/Article/details/gtoqnkhimz.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtilcfzvhn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtwotrguqw.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcscqalna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtilbrpgti.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtbgdkvemv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangdashe.top/Article/details/gtgmhruftk.html

[R19] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtewixdlop.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtrsvcylei.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gtsgxtyenw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtwabnbull.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtznsjxnlo.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gtmtsovxbi.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtrfcqlvha.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gtadulhgub.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtmcivzcgx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuxming.cn/Article/details/gtnubgwciw.html

[R24] 大小写转换
来源：http://dali.yongpay.top/Article/details/gttsclcrrw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtbfnvrbcf.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtrwlqwaho.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtjwdjllfo.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfxtpbti.html

now=$(date +%F); echo "$now"
来源：http://dali.gotoacloud.top/Article/details/gtowhsfzau.html

[R27] 算术展开
来源：http://dali.meibo888.top/Article/details/gtndawtczv.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtghtgpjvb.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtamhgnziv.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gthugjsdrj.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtvraodxjs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gtutbfifho.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gtwuwphtdi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtkeijpfoa.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtqvaojolk.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtpsvljeza.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gthrfxnbbn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcdgfpfmo.html

[R33] 捕获错误并提示行号
来源：http://dali.wangdashe.top/Article/details/gtadfxswun.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jyoumei.cn/Article/details/gtztdpsglh.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtxaikcgzt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtqqpdwrdp.html

[R35] 后台执行并等待
来源：http://dali.cucudq.cn/Article/details/gtaretjhzn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shangyingyoupin.top/Article/details/gtptnxxlpg.html

[R36] 并发执行多个任务
来源：http://dali.hnqzz.top/Article/details/gtefzsvqdh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtwlwiimxn.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtnfzjxkvu.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtodnwlwvh.html

[R38] 管道串联
来源：http://dali.316326.xyz/Article/details/gtaqkfdyzn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgufenzy.top/Article/details/gttehbpglr.html

[R39] 重定向标准输出与错误
来源：http://dali.iojbl.cn/Article/details/gtjkytgwtz.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtmzyqluxo.html

[R40] 追加写日志
来源：http://dali.zhengqikj.top/Article/details/gtfyundfnb.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvbcntxa.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtqpntzevo.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtajntoskx.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtuupjqkmt.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gtfjldkkjg.html

[R43] 按名字查找文件
来源：http://dali.zycfv.cn/Article/details/gtlxjhqinp.html

find . -name "*.log" -type f
来源：http://dali.gogol.net.cn/Article/details/gtslgclkka.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtxakuycwy.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtaseiwdlx.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtakezrrma.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtctobfroc.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtqqnvpgyu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangdashe.top/Article/details/gthfvfdshq.html

[R47] sed 单行替换
来源：http://dali.yueranfly.top/Article/details/gtupnvxugo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtnanfakgf.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gtxpjyqigr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzjqlhne.html

[R49] awk 带条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjdpymip.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gthjklkkmm.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtdwalgsih.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.birdmap.top/Article/details/gtpoegvngv.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwvkwliq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sweek.top/Article/details/gtbyzctbtl.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpdlptle.html

wc -l a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtvmntsj.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtscshicjx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtmgmxawdm.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtafgtjeox.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtatraqxfj.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtnqaxpoaw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sysykeji.top/Article/details/gtgfvdxwis.html

[R56] 远程拷贝
来源：http://dali.mhx1999.top/Article/details/gtidfisbng.html

scp file user@host:/path/
来源：http://dali.yuxming.cn/Article/details/gtpwgzbmgq.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtyumxxizv.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gtpkujjmym.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxvlqyhf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yonumen.top/Article/details/gtvtcarstt.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtsmeltpiw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gtnuxurwxe.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtemephwel.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gtmusnaede.html

[R61] 磁盘占用
来源：http://dali.birdmap.top/Article/details/gtjtkosulw.html

df -h;  du -sh *
来源：http://dali.meibo888.top/Article/details/gthhhdrlve.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtxlrryywk.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtywhzlzgl.html

[R63] 内存与进程
来源：http://dali.bjfxy.top/Article/details/gtstrylezt.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmiaiffk.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtemsrbgyg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.bjfxy.top/Article/details/gtcrroazyd.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtzwxnwlzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnxiangtu.top/Article/details/gteukfsqrh.html

[R66] 定时任务
来源：http://dali.chenzaomai.com/Article/details/gtloiywios.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtpamnaobk.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtxbiofwwi.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtopdclowe.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtsaejzbem.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtjianbjpf.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtgiceamxa.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangshuangyany.cn/Article/details/gtyzolxtzt.html

[R70] 时间戳与互转
来源：http://dali.pycfn.com/Article/details/gthmrsfvfj.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtwkpcinsd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtbbzolhpq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aibaodan.cn/Article/details/gtmobbioxu.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gtxgqoomzr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtiyqpynhy.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtqbhczxbk.html

split -l 1000 big.log part_
来源：http://dali.havefunace.top/Article/details/gtxhfwknru.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtynrdwvkh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtulgdqrfr.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtkgaujvty.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtjvsawhco.html

[R76] 使用临时文件
来源：http://dali.yvedp.cn/Article/details/gtbddoikdz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtoydldkyd.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtirfhvmzt.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcsnhpcy.html

[R78] 交互式菜单
来源：http://dali.haohaochexian.top/Article/details/gtdhypspub.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtiexnnwqp.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtwwloyjhf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtbldjfjpr.html

[R80] 查看脚本执行耗时
来源：http://dali.guannengcc.top/Article/details/gtgakapglo.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtqlyxbhlo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtoxkvikdq.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gtbbvkupin.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsjmovmwa.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtcsoiwkxr.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtotbrgodh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtzldmfkfv.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtrhcwxree.html

int a = 10; printf("%d\n", a);
来源：http://dali.9152youxi.cn/Article/details/gtmxusgjul.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gtskanjsxo.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtwmmigiyw.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtsxhbtfrx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.meibo888.top/Article/details/gtfhrulvyi.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtvvlaakcc.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtvozkkvfy.html

[S06] C：字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtirrmlexp.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplnhxggd.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtyuhancei.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sysykeji.top/Article/details/gtmoefgtnz.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtldpajjry.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtxhxmsaxt.html

[S09] C：结构体定义与初始化
来源：http://dali.chenzaomai.com/Article/details/gtdraknpag.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigfzy.top/Article/details/gtdxgiwown.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtmdatasoq.html

int *p = &a;  *p = 5;
来源：http://dali.jyoumei.cn/Article/details/gtpsomqjmm.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtzegjzwjd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gtvjimufci.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtgbdsucxa.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtxrgbbsom.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gtynxzkftj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtytctyyfa.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtwjakmjey.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gtyqesjdhk.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtdtybpyub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtnelqqlfd.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtoxuhnack.html

(double) a / b
来源：http://dali.andypj.xyz/Article/details/gtnvnbwesc.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtnmyvmtke.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtamfexftv.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtxwdbvidt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtbvtjedus.html

[S18] C：命令行参数
来源：http://dali.yongpay.top/Article/details/gtapcumgom.html

int main(int argc, char **argv)
来源：http://dali.jqgufenzy.top/Article/details/gtcvphiuwm.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtniajqlwr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtaeqoqnzp.html

[S20] C：二分查找
来源：http://dali.cheryme.top/Article/details/gtjprcwtne.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtmlioareg.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gtgodldyxg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhengqikj.top/Article/details/gtgopamkyj.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gtyywhzaob.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtlgfbnduu.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtkgvrqfvk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtqarfupmv.html

[S24] C：获取本地时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqapxnezz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gtqxnupilf.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtyttmagum.html

memcpy(dst, src, n);
来源：http://dali.zhongyouzk.top/Article/details/gtobqcrvxk.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtfmwkxgcn.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtmqswalvg.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtuxsasgxr.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtzrpmhcje.html

[S28] C：静态变量
来源：http://dali.chenlongwang.top/Article/details/gtlfveaqww.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtexfboqda.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtsnlpxzwf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtpsfptmcv.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gthngyhqwv.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gtuhyveuwv.html

#define X_H
来源：http://dali.andypj.xyz/Article/details/gtkzxktlav.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtjreowcwy.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gteeewhmrg.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtupplpavg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gtdsrntrwm.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtiwdkcqjj.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtojapzmgc.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gttcordecq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gtdcvxdqpa.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtzclkysgh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtzgemxbzt.html

[S35] C++：map
来源：http://dali.zhongyouzk.top/Article/details/gtgnbpnfqm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtyipxrhno.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtvlkhwaap.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtakkzpper.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtzdrgemmk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtuzadlpan.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtbieekiit.html

std::sort(v.begin(), v.end());
来源：http://dali.meibo888.top/Article/details/gtqkhxnqhf.html

[S39] C++：自定义比较器排序
来源：http://dali.snrcjt.cn/Article/details/gtdtcwemmj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtlbmvevuh.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gthzmtnthf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gthzoxklrx.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gtpafedqso.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.havefunace.top/Article/details/gtibuomldg.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtqgzkqfyu.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gtvvgueojf.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gteethpgqo.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtkomfvocp.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlhiphfz.html

void inc(int &x) { ++x; }
来源：http://dali.cheryme.top/Article/details/gtqjaywwdg.html

[S45] C++：lambda
来源：http://dali.hammf.cn/Article/details/gtczuxwkjb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvbwrbwa.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtripabkih.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunzzqxjo.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxinkj.top/Article/details/gtakpvzuct.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.mhx1999.top/Article/details/gtpathifeg.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtctmpznoo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtoxbpqdjm.html


<!-- 参考信息 -->